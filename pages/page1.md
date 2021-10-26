---
local1: How to
layout: template_demo
---

[How to Become a Doctor](index.md)

# Studying Western Medicine

{{page.local1}} become a doctor?

{% for study in site.data.medicine %}

-  {{study.school}}: {{study.complete}}

{% endfor %}



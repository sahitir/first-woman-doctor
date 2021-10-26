---
local1: How to
layout: template_demo
---

[Home](index.md) || [More Details](pages/page2.md)

# Studying Western Medicine

{{page.local1}} become a doctor?

{% for study in site.data.medicine %}

-  {{study.school}}: {{study.complete}}

{% endfor %}



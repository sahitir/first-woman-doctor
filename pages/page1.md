---
local1: How to
layout: template_demo
---

[Home](https://sahitir.github.io/first-woman-doctor/) || [More Details](pages/page2.md)

# Studying Western Medicine

{{page.local1}} become a doctor?

{% for study in site.data.medicine %}

-  {{study.school}}: {{study.complete}}

{% endfor %}



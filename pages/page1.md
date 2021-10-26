---
local1: How to
layout: template_demo
---

[Home](https://sahitir.github.io/first-woman-doctor/) || [More Details](https://sahitir.github.io/first-woman-doctor/pages/page2.html)

# Studying Western Medicine

{{page.local1}} become a doctor?

{% for study in site.data.medicine %}

-  {{study.school}}: {{study.complete}}

{% endfor %}



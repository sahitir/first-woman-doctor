---
Doctor1: Kadambini Ganguly
Doctor2: Anandi Gopal Joshi
layout: template_demo
---

<a href="index.md">Home</a> || <a href="page1.md>How to Become a Doctor</a> || <<a href="page2.md>More Details</a>

# India's First Women Doctors

{{page.Doctor1}} and {{page.Doctor2}} were two of _India's first trained women physicians_.

## Kadambini Ganguly

{{page.Doctor1}} was born on July 18, 1861 in Bhagalpur, British India, now Bangladesh. She graduated from **Calcutta Medical College** in 1886. 

## Recognition

{{page.Doctor1}} was a distinguised personality.

- First Indian woman doctor alongside Anandi Gopal Joshi
- Member of the all-women delegation of the India National Congress
- A women's right champion who fought criticisim and opposition to pursue a degree in medicine

![Kadambini_Ganguly](https://user-images.githubusercontent.com/91772418/138817866-34a70868-2e87-40d2-89d7-2e69162777f2.jpg)

Read more about [Kadambini Ganguly](https://en.wikipedia.org/wiki/Kadambini_Ganguly).

## {{page.Doctor2}}

{{page.Doctor2}} was born on March 31, 1865 in Kalyan in British India. She was encouraged by her husband to pursue western medicine and graduated from the [Woman's Medical College of Pennsylvania](https://en.wikipedia.org/wiki/Woman%27s_Medical_College_of_Pennsylvania) in March 1886.

## Life

{{page.Doctor2}} married young and gave birth to a baby boy at the age of fourteen. The boy lived for just ten days due to lack of medical care. This proved to be a turning point in Anandi's life and inspired her to study medicine.

Anandi passed away in 1887 at a young age of twenty-two years from tuberculosis, after just one year of practicing medicine in British India.

![Anandibai_joshi](https://user-images.githubusercontent.com/91772418/138854638-91de3d20-cc65-4d08-9766-b82ff12e7321.jpg)

{% include includefile.txt %}

Read more about [Anandi Gopal Joshi](https://en.wikipedia.org/wiki/Anandi_Gopal_Joshi)

{% for anyword in site.data.life %}

-  {{anyword.doctor}}: {{anyword.birth}}: {{anyword.death}}

{% endfor %}



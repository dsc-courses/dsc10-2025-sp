---
layout: home
title: 🏠 Home
nav_exclude: false
nav_order: 1
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }


{{ site.staffersnobio }}

<!--{: .success }
>Because of holidays, the schedule of important dates is a bit different in the last few weeks! Next week, we have Quiz 4 on Monday, Homework 6 due on Tuesday, and Discussion 8 on Wednesday. -->

<!--{: .success }
>Welcome to DSC 10! Make sure to read this website thoroughly and complete the items in the [Getting Started](https://dsc10.com/syllabus/#-getting-started) checklist. -->


{: .warning }
This site is **under construction**. Anything you read here is not finalized. This disclaimer will be removed when the site is ready for Spring 2025.

<!--{: .success }
>The Final Exam is **this Saturday, December 7th from 11:30AM to 2:30PM**.
>
>Earn 1 participation point by filling out both [SETs](https://academicaffairs.ucsd.edu/Modules/Evals/) and the internal [End-of-Quarter Survey](https://forms.gle/NQ76jTvq9799VvWq8) before Saturday, December 7th at 8AM.-->

<!--{: .success }
>The Midterm Exam is **this Monday, February 10th**. [See announcements here.](https://edstem.org/us/courses/70673/discussion/6127710)
>
>The deadline of the Midterm Project has been extended to **Thursday, February 13th**!
-->

<!--{: .success }
>**Tip**: When working on assignments, use Ctrl+F on this page to search for a keyword and quickly find the relevant lecture. Click the "✏️ write" button to open a static version of the lecture for reference, which is much faster than loading it on DataHub. 
>
>Also, make sure to use the [reference sheet](https://dsc-courses.github.io/bpd-reference/docs/documentation/intro/) to quickly look up `babypandas` methods and see examples of how they work.-->




[Jump to the current week](/#week-10-review){: .btn }


{% for module in site.modules %}
{{ module }}
{% endfor %}
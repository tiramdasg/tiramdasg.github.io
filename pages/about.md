---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
IT professional with 2 years of experience in software development, focusing on data analysis, secure technology integration, and automation. Proven ability to work with international teams, streamline processes, and deliver reliable solutions. Passionate about learning new technologies and applying innovative ideas to solve complex challenges. Dedicated to contributing to impactful projects and attaining relevant skills. <br>
Some of my Hobbies are:
- Wrote poems for a book “Stuttering of Young Adults” published in 2021.
- Developing, publishing, and maintenance of [my blogging site](https://betweentheverses.in) since March, 2020.
<!-- - Listening to electronic pop music / finding new music. -->
- Reading romantic comedy, fiction (science, thriller) novels.
<!-- - Portrait Photography -->
- Playing Cricket
- Travelling
- Badminton
- Organiser of meet-up events 

## Languages
* English (C2, Native Proficiency)
* Korean (B2, Advanced Proficiency)
* German (B1.1, Intermediate Proficiency)
* Japanese (A1, Beginner Proficiency)
* Hindi, Telugu (Native)
<!-- CEFR descriptions -->

<!-- skills -->
<div class="row">
{% include about/skills.html title="Programming" source=site.data.programming-skills %}
</div>

<div class="row">
{% include about/skills.html title="Platforms and Tools" source=site.data.tools-platforms-skills %}
</div> 

<div class="row">
{% include about/skills.html title="Operating Systems" source=site.data.data-sw-mgmt-skills %}
</div>

<!-- education -->
<div class="row">
{% include about/timeline.html title="Education" source=site.data.timeline-edu %}
</div>

<!-- work experience -->
<div class="row">
{% include about/timeline.html title="Employment History" source=site.data.work-experience %}
</div>

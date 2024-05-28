---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
Aspiring Software Engineer Specialist with full capabilities of integrating technologies in a secure and transparent manner. Acquiring latest skills to achieve this through education, projects, research, and work experience. Passionate about tackling challenges with tailored, innovative personalized solutions while learning and contributing.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.dev-programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.tools-platforms-skills %}
</div>

<div class="row">
{% include about/timeline.html title="Work Experience" source=site.data.work-experience.yml %}
</div>
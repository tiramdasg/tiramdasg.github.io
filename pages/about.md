---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
IT professional with 2 years of experience in software development, focusing on data analysis, secure technology integration, and automation. Proven ability to work with international teams, streamline processes, and deliver reliable solutions. Passionate about learning new technologies and applying innovative ideas to solve complex challenges. Dedicated to contributing to impactful projects and attaining relevant skills. <br>

### A Day of My Life
<img src="{{ '/assets/images/day_of_life_chart.png' | relative_url }}" alt="A Day of My Life" style="max-width:200px;">

## Languages

<table>
  <tr><td><strong>English</strong> (Native)</td><td>⬤⬤⬤⬤⬤</td></tr>
  <tr><td><strong>German</strong> (B1.1 - Actively Improving)</td><td>⬤⬤⬤⚪⚪</td></tr>
  <tr><td><strong>Korean</strong> (Advanced, B2)</td><td>⬤⬤⬤⬤⚪</td></tr>
  <tr><td><strong>Japanese</strong> (Beginner, A2)</td><td>⬤⬤⚪⚪⚪</td></tr>
  <tr><td><strong>Telugu, Hindi</strong> (Native)</td><td>⬤⬤⬤⬤⬤</td></tr>
</table>


<!-- work experience -->
<div class="row">
{% include about/timeline.html title="Experience" source=site.data.work-experience %}
</div>

<!-- education -->
<div class="row">
{% include about/timeline.html title="Education" source=site.data.timeline-edu %}
</div>

<!-- skills -->
<div class="row">
{% include about/skills.html title="Programming" source=site.data.programming-skills %}
</div>

<div class="row">
{% include about/skills.html title="Platforms and Tools" source=site.data.tools-platforms-skills %}
</div> 

<div class="row">
{% include about/skills.html title="AI & Data Engineering" source=site.data.ai-data-engg-skills %}
</div>

<div class="row">
{% include about/skills.html title="Web Development" source=site.data.web-dev-skills %}
</div>

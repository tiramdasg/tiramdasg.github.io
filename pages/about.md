---
layout: page
title: About
permalink: /about/
weight: 4
---

# **About Me**
Hi I am **{{ site.author.name }}** :wave:,<br>
Curious Software Engineer with hands-on experience in R&D and full-stack development. Skilled in Python, RESTful APIs, automation, ML, cloud platforms, and SCM using Git. I thrive on solving problems with creative solutions and excel at collaborating to drive meaningful contributions. Committed to continuous learning and clear stakeholder communication. <br>

<section aria-labelledby="cv-heading" class="mb-4">
  <h3 id="cv-heading" class="mb-4">Curriculum Vitae</h3>
  <ul class="list-unstyled" role="list">
    {% for item in site.data.work-experience %}
    <li class="row mb-4">
      <div class="col-sm-3 mb-1 mb-sm-0">
        {{ item.from | escape }}{% if item.to and item.to != empty %} — {{ item.to | escape }}{% endif %}
      </div>
      <div class="col-sm-9">
        <h3 class="h5 mb-1">{{ item.title | escape }}</h3>
        <p class="mb-1">{{ item.location | escape }}</p>
        {% if item.type and item.type != empty %}
        <p class="font-italic mb-0">{{ item.type | escape }}</p>
        {% endif %}
      </div>
    </li>
    {% endfor %}
  </ul>
</section>

<!-- work experience -->
{% comment %}
<div class="row">
{% include about/timeline.html title="Experience" source=site.data.work-experience %}
</div>
{% endcomment %}

<!-- education -->
{% comment %}
<div class="row">
{% include about/timeline.html title="Education" source=site.data.timeline-edu %}
</div>
{% endcomment %}

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

### Languages

<table>
  <tr><td><strong>English</strong> (Native)</td><td>⬤⬤⬤⬤⬤</td></tr>
  <tr><td><strong>German</strong> (B1.1 - Actively Improving)</td><td>⬤⬤⬤⚪⚪</td></tr>
  <tr><td><strong>Korean</strong> (Advanced, B2)</td><td>⬤⬤⬤⬤⚪</td></tr>
  <tr><td><strong>Japanese</strong> (Beginner, A2)</td><td>⬤⬤⚪⚪⚪</td></tr>
  <tr><td><strong>Telugu, Hindi</strong> (Native)</td><td>⬤⬤⬤⬤⬤</td></tr>
</table>

<!-- ### A Day of My Life
<img src="{{ '/assets/images/day_of_life_chart.png' | relative_url }}" alt="A Day of My Life" style="max-width:400px;"> -->


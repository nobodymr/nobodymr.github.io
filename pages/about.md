---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About**
Hi I am **{{ site.author.name }}** :wave:,<br>
and Welcome to my portfolio-site! I am working with Server Administration, Data Analysis & Visualization, Web & Mobile Development, Graphic & Concept Design, 2D & 3D Modeling.

If You have some work for me, please, <a href="mailto:d.jalilzoda@mail.ru">let me know</a>!

{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Frameworks I use" source=site.data.frameworks %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}

<div class="row">
{% include about/timeline.html %}
</div>
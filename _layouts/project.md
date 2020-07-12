---
layout: default
---

{% if page.image %}<img class="w-100 mt-5" src="{{ page.image }}">{% endif %}
<div class="col-lg-10 mx-auto mt-5 post">
<h1>{{ page.name }}</h1>
{% for tool in page.tools %}<span class="badge badge-primary mr-1">{{ tool }}</span>{% endfor %}
<p class="mt-3">{{ page.description }}</p>
<hr>
{{ content }}
</div>
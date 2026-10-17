---
layout: default
title: Guide des notes et des familles olfactives
description: Hespéridées, florales, boisées, orientales : apprenez à reconnaître les notes d'un parfum et à choisir celles qui vous correspondent.
---
# Les notes d'un parfum, expliquées simplement

Chaque parfum est une composition de notes regroupées en grandes familles. Ce guide vous aide à les reconnaître, à les nommer et à trouver celles qui vous plaisent.

<ul class="posts">
{% for post in site.posts %}
<li class="fam-{{ post.famille }}"><a href="{{ post.url }}">{{ post.title }}</a><p>{{ post.description }}</p></li>
{% endfor %}
</ul>

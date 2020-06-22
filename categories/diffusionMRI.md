---
layout: page
title: diffusionMRI
permalink: /blog/categories/diffusionMRI
---

<h5> Posts by Category : {{ page.title }} </h5>

<div class="card">
{% for post in site.categories.diffusionMRI %}
 <li class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</div>

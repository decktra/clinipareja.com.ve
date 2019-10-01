---
layout: default
title: "Inicio"
---

{% include carousel.html %}
{% include instagram.html %}
{% include banner.html %}
{% include testimonies.html %}
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>


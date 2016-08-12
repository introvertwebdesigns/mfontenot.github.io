---
layout: splash
title: "Blog"
excerpt: "...a place for thoughts"
permalink: /blog/
---

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}

{% include paginator.html %}

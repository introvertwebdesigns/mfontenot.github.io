---
layout: archive
title: "Mike's Blog"
permalink: /blog/
---

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
permalink: /til/
title: "Today I Learned"
date: 2016-10-21T12:12:10-04:00
modified:
excerpt: "Learnings (sometimes daily) captured for posterity and educational purposes."
---

{% for post in site.categories.til %}
  {% include archive__item.html %}
{% endfor %}

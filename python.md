---
layout: page 
title: Python 
permalink: /python/
---

This contains all the python links

{% for p in site.python %}
  [{{ p.title }}]({{p.url}})
{% endfor %}

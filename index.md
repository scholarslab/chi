---
layout: default
title: Home
---

Browse records

{% for record in site.records %}
<a href="{{ site.baseurl }}/records/{{ record.slug }}">{{ record.title }}</a>
{% endfor %}

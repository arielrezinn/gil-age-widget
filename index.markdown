---
layout: default
---

{% for widget in site.pages %}
<a href="{{ widget.url }}">{{ widget.title }}</a>
{% endfor %}

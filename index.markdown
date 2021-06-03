---
layout: default
---

{% for widget in site.pages %}
<a href="{{ site.baseurl }}{{ widget.url }}">{{ widget.title }}</a>
{% endfor %}

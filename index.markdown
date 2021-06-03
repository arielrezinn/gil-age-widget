---
layout: default
---

{% for widget in site.pages %}

## [{{ widget.title }}]({{ site.baseurl }}{{ widget.url }})

> {{ widget.description }}

{% endfor %}

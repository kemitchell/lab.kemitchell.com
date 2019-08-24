---
layout: default
---

## Lab Partners

If you're planning to try a new funding experiment, and would like feedback or moral support during launch, [e-mail me](mailto:kyle@kemitchell.com).  I'll be happy to talk, and to connect you with others behind initiatives on this list.

## Experiments

{% for project in site.projects reversed %}
{% include project.html %}
{% endfor %}

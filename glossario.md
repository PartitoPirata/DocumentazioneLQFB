---
---
# Glossario

<dl>
{% assign glossario = site.data.glossario | sort: "term" %}
{% for term in glossario %}
<dt id="{{ term.term | slugify }}">{{ term.term }} <a href="#{{ term.term | slugify }}">#</a></dt>
<dd>{{ term.definition | markdownify }}</dd>
{% endfor %}
</dl>

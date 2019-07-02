---
---
# Glossario

<dl>
{% for term in site.data.glossario %}
<dt id="{{ term.term }}">{{ term.term }}</dt>
<dd>{{ term.definition }}</dd>
{% endfor %}
</dl>

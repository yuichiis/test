## test/docs/readme

### Theme
: {{ site.theme }}

### site data in _config.yml

{% for collection in site.collections %}
- ( {{ forloop.index }} : {{ collection.title }} )
{% endfor %}

<div>
  - list
  - list
</div>

- list
- list

word
:  define
word
:  description

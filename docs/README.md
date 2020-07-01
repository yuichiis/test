## test/docs/readme

[Check it out][ghpages]

### Theme
: {{ site.theme }}

### site data in _config.yml

{% for collection in site.collections %}
- ( {{ forloop.index }} : {{ collection.title }} )
{% endfor %}

- list
- list

<div>
  - list
  - list
</div>

{::options parse_block_html="true" /}
<div>
- list
- list
</div>

word
:  define
word
:  description

[ghpages]: https://yuichiis.github.io/test/ (Published this page)

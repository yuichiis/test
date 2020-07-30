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

![image](image.png)

![image](image2.png)
=======
[ghpages]: https://yuichiis.github.io/test/

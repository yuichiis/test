# test
{{ site.theme }}
{% for collection in site.collections[1] %}
( {{ forloop.index }} : {{ collection }} ) <br>
{% endfor %}

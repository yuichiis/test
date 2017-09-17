# test
{{ site.theme }}
{% for collection in site.collections %}
( {{ forloop.index }} : {{ collection.title }} ) <br>
{% endfor %}

# test
{{ site.theme }}
{% for collection in site.collections %}
( {{ collection[0] }} : {{ collection[1] }} ) <br>
{% endfor %}

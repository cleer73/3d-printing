<h1>3D Printing Projects</h1>

{% for print in site.prints %}
- [{{ print.title }}]({{ print.url | absolute_url}})
{% endfor %}

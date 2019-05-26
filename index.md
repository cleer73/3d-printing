<h1>3D Printing Projects</h1>

<ul>
{% for print in site.prints %}
  <li><a href="{{ print.url }}">{{ print.title }}</a></li>
{% endfor %}
</ul>

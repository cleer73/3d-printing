<h1>3D Printing Projects</h1>

{% for print in site.prints %}
  <h2>
    <a href="{{ print.url }}">
      {{ print.title }}
    </a>
  </h2>
{% endfor %}
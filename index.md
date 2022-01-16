<ul>
  {% for page in site.html_pages %}
    {% if page.layout == "page" %}
      <li>
        <a href=".{{ page.url }}">{{ page.title }}</a>
        {{ page.date }}
      </li>
    {% endif %}
  {% endfor %}
</ul>　　

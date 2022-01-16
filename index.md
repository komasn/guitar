<p>メジャーコード</p>
<ul>
  {% for page in site.html_pages %}
    {% if page.category == "メジャーコード" %}
      <li>
        <a href=".{{ page.url }}">{{ page.title }}</a>
        {{ page.date }}
      </li>
    {% endif %}
  {% endfor %}
</ul>

<p>マイナーコード</p>
<ul>
  {% for page in site.html_pages %}
    {% if page.category == "マイナーコード" %}
      <li>
        <a href=".{{ page.url }}">{{ page.title }}</a>
        {{ page.date }}
      </li>
    {% endif %}
  {% endfor %}
</ul>

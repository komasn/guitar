<ul>
  {% for post in site.posts %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
      {{ post.date }}
    </li>
  {% endfor %}
</ul>　　

<ul>
  {% for page in site.html_pages %}
    <li>
      <a href=".{{ page.url }}">{{ page.title }}</a>
      {{ page.date }}
    </li>
  {% endfor %}
</ul>　　

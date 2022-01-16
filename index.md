<ul>
  {% for post in site.posts %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
      {{ post.date }}
    </li>
  {% endfor %}
</ul>　　

<ul>
  {% for post in site.pages %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
      {{ post.date }}
    </li>
  {% endfor %}
</ul>　　

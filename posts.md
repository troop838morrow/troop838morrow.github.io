<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date }} - {{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

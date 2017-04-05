<ul>
  {% for post in site.posts %}
    <li>
      !(/img/eagle_menu.png) <a href="{{ post.url }}">{{ post.date | date: "%-m/%-d/%Y" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{% for post in site.posts %}
  <h3>{{ post.date | date: "%-m/%-d/%Y" }} - {{ post.title }}</h3>
  {{ post.content }}
  <hr>
{% endfor %}

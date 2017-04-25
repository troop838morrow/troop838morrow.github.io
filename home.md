{% for post in site.posts %}
  <h2>{{ post.date | date: "%-m/%-d/%Y" }} - {{ post.title }}</h2>
  {{ post.content }}
  <hr>
{% endfor %}

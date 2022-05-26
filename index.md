<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.content[:100] }}
    </li>
  {% endfor %}
</ul>

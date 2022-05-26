<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <div style="background-color:#FAF0D7; padding: 20px">
        {{ post.content }}
      </div>
    </li>
  {% endfor %}
</ul>

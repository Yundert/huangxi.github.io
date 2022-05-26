<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <div style="color:grey">
        {{ post.content }}
      </div>
    </li>
  {% endfor %}
</ul>

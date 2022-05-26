
  {% for post in site.posts %}
      <div style="background-color:#FAF0D7; padding: 20px">
        <a href="{{ post.url }}">{{ post.title }}</a> <br>
        {{ post.date }} <br> 
        {{ post.abstract }}
      </div>
      <br>
  {% endfor %}

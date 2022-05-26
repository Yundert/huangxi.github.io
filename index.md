<ul>
  {% for post in site.posts %}
    <li style="list-style:none">
      <div style="background-color:#FAF0D7; padding: 20px">
        <a href="{{ post.url }}">{{ post.title }}</a> <br>
        Posted on {{ post.pdate }} <br><br> 
        {{ post.abstract }}
      </div>
      <br>
    </li>
  {% endfor %}
</ul>
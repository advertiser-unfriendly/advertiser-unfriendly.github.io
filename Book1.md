<ul>
  {% for post in site.hallowed1 %}
    <li>
    ![{{ post.title }}]({{ post.url }})
    </li>
  {% endfor %}
</ul>
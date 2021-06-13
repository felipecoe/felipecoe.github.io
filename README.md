Hi there. This is a space for thought and reflection on information security and leadership.

Check this [about page](/about)

## Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

Hello world

<ul class="posts">
  {% for post in site.posts %}
    <li class="post">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <time class="publish-date" datetime="{{ post.date | date: '%F' }}">
        {{ post.date | date: "%B %-d, %Y" }}
      </time>
    </li>
  {% endfor %}
</ul>

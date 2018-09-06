## Past Blog Posts

...
<ul>
  {% for post in site.posts %}
    <li>
      
      <h4>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
      - <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
      
      </h4>
      
    </li>
  {% endfor %}
</ul>
...

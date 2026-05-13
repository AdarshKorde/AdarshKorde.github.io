```markdown
# Welcome to My Portfolio

I am a robotics engineer focusing on Vision-Language-Action models and control systems. 

## Recent Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>

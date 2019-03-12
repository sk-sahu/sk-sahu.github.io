---
layout: default
---

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>

      <div class="date">
        writen on {{ post.date | date: "%B %e, %Y" }}
      </div>
      
    </article>
  {% endfor %}
</div>

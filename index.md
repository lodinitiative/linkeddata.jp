---
layout: page
---
{% for post in site.posts %}
  <section>
    <h2><a class="post-link" href="{{ post.url }}">{{ post.title }}</a></h2>
    <div class="date">{{ post.date | date_to_string }}</div>
    <p>{{ post.excerpt }}</p>
  </section>
{% endfor %}

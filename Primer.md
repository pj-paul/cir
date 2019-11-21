---
layout: page
title: Primer
---

<div class="toc">
  <h2>Primer</h2>
  <ul class="texts">
{% for post in site.categories.primer %}
    <li><a href="{{ post.url | prepend:site.baseurl }}">{{ post.title }}</a> &nbsp; {{ post.date | date_to_string }}</li>
{% endfor %}
</ul>
</div>

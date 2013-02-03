---
layout: page
title: The Happenings
tagline: File:/// like if you are on OS X
---
{% include JB/setup %}

## Like trying new things?
    
    ssh ctf@54.235.161.29
      04may13
    
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



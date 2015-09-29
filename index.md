---
layout: page
title: Fermium
tagline: From community, for community
---
{% include JB/setup %}

The Fermium team is a group of highly talented developers who are passionate about delivering open source solutions based on bleeding edge technologies.

But it's not just the core team, Fermium is driven forward by occasional contributors and its sponsor.

**Goals:**

* Since the beginning, we've focused on providing our framework & tools on GitHub.

* Framework and tools are being developed in:

    Modern JavaScript
    
    .NET and Core CLR
    
    Python
    
* Knowledge sharing through this blog

Get involved in (your) open source projects through GitHub at https://github.com/Fermium-co

Feel free to leave your feedbacks on blog posts or send your tweets to [@fermium_co](http://twitter.com/fermium_co)

Recent blog posts:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
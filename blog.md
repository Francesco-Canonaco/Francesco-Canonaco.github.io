---
layout: default
title: Blog
---

# Blog Posts

<ul style="list-style-type: none; padding-left: 0;">
  {% for post in site.posts %}
    <li style="margin-bottom: 20px;">
      <span style="color: #888; margin-right: 15px;">{{ post.date | date: "%b %d, %Y" }}</span>
      <a href="{{ post.url }}" style="font-weight: 500; font-size: 1.1em; text-decoration: none; color: #2c3e50;">
        {{ post.title }}
      </a>
    </li>
  {% endfor %}
</ul>
---
layout: default
title: My blog :D
---

# My blog is a place where I can ramble my long form thoughts into a markdown file then post it out for the world to see.
A lot of these posts come from random thoughts and ideas at 3am when I just physically cannot sleep or when I'm in the shower. You know, the usual.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<footer>
    <h6><a href="/">Click here to go back.</a></h6>
</footer>

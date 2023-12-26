---
layout: default
title: My literature work
---

## From time to time, I may write works such as poetry, short stories, and other things of that sort.
This page acts as an archive of all of those.

<ul>
  {% for page in site.collections.literature %}
    <li>
      <a href="{{ page.url }}">{{ page.title }}</a>
    </li>
  {% endfor %}
</ul>

<footer>
    <h6><a href="/">Click here to go back.</a></h6>
</footer>
---
layout: home
title: Home
---
<figure>
  <img src="{{ '/assets/images/antigua-and-barbuda-flag.jpg' | relative_url }}"
     alt="Historical picture of Antigua and Barbuda">
  <figcaption>"Historic architecture in St. John's, Antigua showing the flag".</figcaption>
</figure>


# Discover Antigua and Barbuda

**Antigua and Barbuda: Our history,
our culture, our identity.**

Welcome to the Antigua and Barbuda Heritage Journal
a blog celebrating the independence of Antigua and Barbuda.

Explore the journey to independence,the traditions of our people and the national symbols that shape our identity.Discover why independence remains a part of our national story.

Our history is part of who we are.
Our culture connects us.
Our independence shapes our future.

<h2>Recent stories</h2>
<ul>
  {% for post in site.posts %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

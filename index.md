---
layout: default
title: GalaxyTek Hires
---

<div class="container">
  {% for post in site.posts %}
  <div class="job-post">
    <div class="job-title">{{ post.title }}</div>
    <div class="job-location">{{ post.location }}</div>
    <p>{{ post.excerpt }}</p>
    <a href="{{ post.url }}">View full post</a>
  </div>
  {% endfor %}

  <div class="contact">
    <p>Interested in a role? Reach out to us on LinkedIn:</p>
    <a href="https://www.linkedin.com/company/galaxytek-hires" target="_blank">Contact GalaxyTek Hires</a>
  </div>
</div>

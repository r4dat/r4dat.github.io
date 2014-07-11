---
layout: page
title: Archive
sitemap:
  priority: 0.7
  changefreq: weekly

---
  {% for post in site.posts %}
  <p>
      [{{ post.title }}]({{ post.url }})
  </p>
  {% endfor %}

---
layout: page
sitemap:
  priority: 0.7
  changefreq: weekly
  lastmod: 2011-09-29T18:56:19+02:00
---
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
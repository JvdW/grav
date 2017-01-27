---
title: Blog
sitemap:
    changefreq: monthly
    priority: 1.03
content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    limit: 5
    pagination: true
    show_date: false
feed:
    description: 'Puzzle-IT blog'
    limit: 10
pagination: true
process:
    markdown: true
    twig: true
---

{% for p in page.collection %}
<h2>{{ p.title }}</h2>
{{ p.summary }}
{% endfor %}
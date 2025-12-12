---
title: Blog
blog_url: blog
body_classes: header-image fullwidth

sitemap:
    changefreq: monthly
    priority: 1.03

content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 6
    pagination: true

feed:
    description: Sample Blog Description
    limit: 10

pagination: true

slider:
    -
        image: slide3.jpg
        title: A very delicious blog
        url: '#'
    -
        image: slide1.jpg
        title: Duis autem
        url: '#'
    -
        image: slide2.jpg
        title: Pumpkin recipe
        url: '#'
---

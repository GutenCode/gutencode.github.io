---
layout: default
---

<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  </head>
  <body>
    <ul>
      {% for post in site.posts %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        Published on {{ post.date | date: "%B %d, %Y" }}
      </li>
      {% endfor %}
    </ul>
  </body>
</html>
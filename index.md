---
layout: default
---
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Barlow:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="{{ '/assets/css/screen.css' | relative_url }}">
</head>
<body>
    <h2>Product Management</h2>
    <ul class = "posts">
        {% for post in site.posts %}
        <li>
            <span>
                <a href="{{ post.url }}">{{ post.title }}</a>
            </span>
        </li>
        {% endfor %}
    </ul>
</body>
</html>

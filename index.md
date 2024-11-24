---
layout: default
---
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css?family=Comfortaa:400,700" rel="stylesheet">
    <link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">
</head>
<body>
    <h1>Posts</h1>
    <ul>
        {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
        {% endfor %}
    </ul>
</body>
</html>

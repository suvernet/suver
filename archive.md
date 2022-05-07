---
layout: page
title: Архив
---
<head>
  <!-- CSS -->
  <link rel="stylesheet" href="/public/css/style.css">

</head>

{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}

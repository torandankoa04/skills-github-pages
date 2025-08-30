---
title: Welcome to my blog
---

# Hello my name is Khoa
## A journey of a thousand miles begins with a single step
---
# About me:
- Living in Vietnam
- Studying IT (Python, C++, C#,..)
---
# Things that I like:
- Anime
- Fiction Games and Movie
- Youtube Video

---
## Blog Posts
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%Y-%m-%d" }})
{% endfor %}

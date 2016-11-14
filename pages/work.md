---
layout: default
permalink: /work.html
---
{% assign posts = site.posts | where:"type", "work" %}

<ul>
{% for post in posts %}
<li>
<a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
<ul>
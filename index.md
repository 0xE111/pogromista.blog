----
layout: post
title: Блог погромиста
----
{% for post in site.posts %}
    * [{{ post.title }}]({{ post.url }})
{% endfor %}

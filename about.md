---
layout: page
title: Demo
---

<ul class="arc-list">
    {% for post in demo.last %}
        <li>{{ post.date | date:"%d/%m/%Y"}}<a href="{{ post.url }}"> {{ post.title }}</a></li>
    {% endfor %}
</ul>

---
layout: page
title: Demo
---

<h4>Category</h4>
<ul>
    {% for category in site.categories %}
    <li>
    <a href="/category/{{ category }}" title="view all posts">{{ category | first }} </a>
    <span>({{ category | last | size =}})</span>
    </li>
    {% endfor %}
</ul>

---
layout: page
title: Demo
---

<h4>Category</h4>
<ul>
    {% for category in site.categories %}
    <li>
    <a href="/categories/{{ category | first }}/" title="view all posts">{{ category | first }} </a>
    <span>({{ category | last | size =}})</span>
    </li>
    {% endfor %}
</ul>

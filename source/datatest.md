---
layout: default
title: "Data test"
permalink: "/datatest"
---

{% for item in site.data.datatest.csv %}
    <a href = item.link>
        <img src = item.img>
    </a>
    <div>
        item.quote
    </div>
{% endfor %}
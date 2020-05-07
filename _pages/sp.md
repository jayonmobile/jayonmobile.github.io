---
layout: post
title: "SP 500"
author: "Chester"
permalink: /sp500/
---

SP500 Chart here

![Down -0.7%](/assets/sp500chart.png)

<ul>
{% for member in site.data.members %}
  <li>
    <a href="https://github.com/{{ member.github }}">
      {{ member.name }}
    </a>
  </li>
{% endfor %}
</ul>
---
title: "Blog"
description: "Blog by Sheikh Abdul Munim covering AI, robotics, ROS, and autonomous systems."
keywords: "AI Blog, Robotics Blog, ROS2, Tiago Robot, NLP, AI Planning, Sheikh Abdul Munim"
author: "Sheikh Abdul Munim"
---


# 📝 Blog

Welcome to my blog where I share my thoughts, project updates, and experiences.

---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>

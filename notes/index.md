---
layout: default
title: Notes
---

# 📝 Notes

Welcome to my cognitive psychology notes. Browse by date:

{% assign postsByYearMonth = site.posts | group_by_exp:"post", "post.date | date: '%Y %B'" %}
{% for yearMonth in postsByYearMonth %}
## {{ yearMonth.name }}
<ul>
{% for post in yearMonth.items %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <span class="post-date">{{ post.date | date: "%B %d, %Y" }}</span>
  </li>
{% endfor %}
</ul>
{% endfor %}

---

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

## All Notes (Original Links)

- [Language and the Brain](./language_and_the_brain/)
- [Disembodied vs. Embodied Meaning](./disembodied_vs_embodied/)
- [Modality-Specific vs. Nonspecific Areas](./brain_areas_and_modality/)
- [Perception as Modular](./modular_perception/)
- [Simulation Hypothesis](./embodied_simulation/)
- [Challenges to Traditional Views](./challenges_to_traditional_views/)
- [Symbol Grounding Problem](./symbol_grounding_problem/)
- [Testing Embodied Cognition](./testing_embodiment/)
- [About Chat Ferry](./about_chat_ferry/)
- [Chat Ferry story](./chat_ferry_story/)
- [The Chicken Flock Effect](./chicken_flock_effect/)
- [Festinger's Rule](./festingers_rule/)

---
layout: home
---

Tech Enthusiast and Software Engineer. Currently building Sophi 👩‍💻 ([@sophi.app](https://sophi.app)). I write about my thoughts, life experiences and technical insights.

## 📝 Latest Posts

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## 🌱 What I Write About

- **Personal Journey**: Stories and reflections from my life experiences
- **Tech Insights**: Coming soon - Deep dives into technical concepts and learnings
- **Random Musings**: Thoughts on various topics that intrigue me 
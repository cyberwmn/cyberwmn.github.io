---
layout: default
title: Home
---

## 👋 Welcome

This is my **cybersecurity blog** where I post:

- 🛡️ CTF walkthroughs  
- 🔍 SOC & blue team notes  
- 🧪 Tools and experiments  
- 🧠 What I learn along the way  

---

## 📝 Latest Posts

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})**  
  <span style="color:#8b949e;">{{ post.date | date: "%B %d, %Y" }}</span>
{% endfor %}

---
layout: default
title: Blog
---

# 📰 Nos articles

Bienvenue sur notre espace blog !  
Retrouvez ici tous nos articles autour de la **cybersécurité**, de la **conformité** et de l’**IA appliquée**.  

---

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%d/%m/%Y" }})
{% endfor %}

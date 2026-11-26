---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Postdoctoral Researcher at NYU Abu Dhabi, where I am a member of the [SANAD (Software Analysis and Developer Support) Lab](https://sanadlab.org). I am also an external researcher at HASLab/INESC TEC.

My research focuses on software analysis, especially from a performance and security point of view. I build automated analysis techniques and tools that help developers find and fix problems in their code. Most of my work targets mobile (Android) applications. My recent papers also study LLM-generated mobile code and LLM agents that build Android apps.

I got my PhD in Computer Science from the University of Minho in 2024.


News
======

{% include news-list.html limit=5 %}

[All news](/news/)


Selected publications
======

{% assign selected = site.data.publications | where: "selected", true %}
<ul class="pub-list">
{% for pub in selected %}{% include publication.html pub=pub show_year=true %}{% endfor %}
</ul>

[All publications](/publications/)


Research interests
======

- Software Analysis
- Software Performance
- Software Security
- Automated Software Engineering
- Software Testing and Evolution
- Green Computing
- Mining Software Repositories
- Mobile Software Development
- Distributed Systems

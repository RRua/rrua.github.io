---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my [Google Scholar profile](https://scholar.google.pt/citations?user=NvJ7KjYAAAAJ).

{% assign years = site.data.publications | group_by: "year" %}
{% for year in years %}
<h2>{{ year.name }}</h2>
<ul class="pub-list">
{% for pub in year.items %}{% include publication.html pub=pub %}{% endfor %}
</ul>
{% endfor %}

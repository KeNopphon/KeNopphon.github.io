---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

My complete and most up-to-date list of publications is maintained on <u><a href="{{ author.researchmap }}">researchmap</a></u>. You can also find my articles on <u><a href="{{ author.googlescholar }}">my Google Scholar profile</a></u>.

{% assign sections = "journal:Journal Articles|conference:International Conference Proceedings|book:Book Chapters|preprint:Preprints|thesis:Theses" | split: "|" %}
{% for s in sections %}
{% assign key = s | split: ":" | first %}
{% assign heading = s | split: ":" | last %}
{% assign items = site.publications | where: "pubtype", key | reverse %}
{% if items.size > 0 %}
<h2>{{ heading }} ({{ items.size }})</h2>
{% for post in items %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}
{% endfor %}

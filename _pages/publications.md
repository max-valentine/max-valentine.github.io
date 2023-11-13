---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
toc_label: Research timeline
toc_icon: dna
toc: true
classes: wide
---

You can also find my publications on <u><a href="https://researchportal.bath.ac.uk/en/persons/max-valentine" target="_blank" rel="noopener">my ResearchPortal website</a>.</u>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

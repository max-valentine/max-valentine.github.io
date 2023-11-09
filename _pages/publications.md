---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my publications on <u><a href="https://researchportal.bath.ac.uk/en/persons/max-valentine">my ResearchPortal website</a>.</u>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

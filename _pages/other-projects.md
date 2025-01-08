---
layout: archive
title: "Other Projects"
permalink: /other-projects/
author_profile: true
---

Here is a list of my other projects that I am currently working on or have completed in the past.

{% include base_path %}

{% for project in site.data.other_projects %}
  <h3>{{ project.title }}</h3>
  <p>{{ project.description }}</p>
  <a href="{{ project.url }}">Learn More</a>
  <hr>
{% endfor %}
---
layout: archive
title: "Portfolio"
permalink: /portfolio/
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


### Bibliography Cleaner and Sorter
This tool helps you to clean and sort your .bib files automatically. Use it directly from this page:

<iframe src="YOUR_STREAMLIT_APP_URL" width="100%" height="800" frameborder="0">
  Sorry, your browser does not support inline frames.
</iframe>
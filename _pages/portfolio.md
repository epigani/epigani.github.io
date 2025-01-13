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
This tool helps you to clean and sort your .bib files automatically. 
Access the app [here](https://bib-cleaner.streamlit.app/) or use it directly from this page:

<iframe src="https://bib-cleaner.streamlit.app/" width="100%" height="800" frameborder="0">
    This browser does not support embedded web pages. Click <a href="https://bib-cleaner.streamlit.app/">here</a> to open the app in a new tab.
</iframe>

<!-- <iframe src="https://bib-cleaner.streamlit.app/" width="100%" height="800" frameborder="0">
  Sorry, your browser does not support inline frames.
</iframe> -->


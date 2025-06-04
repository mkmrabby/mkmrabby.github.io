---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

You can also find my articles on <a href="https://scholar.google.com/citations?user=YCHJZOMAAAAJ&hl=en" target="_blank">my Google Scholar profile</a>. (* indicates equal contribution)

{% include base_path %}

{% assign current_year = site.time | date: "%Y" %}
{% assign publicationsByYear = site.publications | group_by_exp:"post", "post.date | date: '%Y'" %}

<h1 style="margin: 1.25em 0px -0.5em; padding: 0px; color: brown;">Recent Preprints</h1>
{% assign current_year = site.time | date: "%Y" %}
{% for post in site.publications reversed %}
  {% assign post_year = post.date | date: "%Y" %}
  {% if post.venue == "arXiv" and post_year == current_year %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<hr>
{% for year in publicationsByYear reversed %}
  <h1 style="margin: 1.5em 0px -0.5em; padding: 0px; color: brown;">{{ year.name }}</h1>
  {% assign publicationsByMonth = year.items | group_by_exp:"post", "post.date | date: '%B'" %}
  {% for month in publicationsByMonth reversed %}
    {% for post in month.items reversed %}
      {% if post.venue != "arXiv" and post.venue != "UCLA Electronic Theses and Dissertations" %}
        {% include archive-single.html %}
      {% endif %}
    {% endfor %}
  {% endfor %}
{% endfor %}

<hr>
<h1 style="margin: 1.25em 0px -0.5em; padding: 0px; color: brown;">Older Preprints</h1>
{% assign current_year = site.time | date: "%Y" %}
{% for post in site.publications reversed %}
  {% assign post_year = post.date | date: "%Y" %}
  {% if post.venue == "arXiv" and post_year < current_year %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<hr>
<h1 style="margin: 1.25em 0px -0.5em; padding: 0px; color: brown;">Dissertation</h1>
{% for post in site.publications reversed %}
  {% if post.venue == "UCLA Electronic Theses and Dissertations" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


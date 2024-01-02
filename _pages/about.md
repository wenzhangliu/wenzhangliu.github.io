---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- {% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %} -->

<span class='anchor' id='about-me'></span>
{% include_relative sources/brief_bio.md %}

{% include_relative sources/news.md %}

{% include_relative sources/publications.md %}

<span class='anchor' id='cn-patents'></span>
{% include_relative sources/cn_patents.md %}

{% include_relative sources/honors_and_awards.md %}

{% include_relative sources/educations.md %}

<span class='anchor' id='invited-talks'></span>
{% include_relative sources/invited_talks.md %}

{% include_relative sources/internships.md %}

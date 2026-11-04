---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

## Pages

{% for link in site.data.navigation.main %}
- [{{ link.title }}]({{ link.url | relative_url }})
{% endfor %}

## Research

{% assign papers = site.publications | sort: 'display_order' %}
{% for paper in papers %}
- [{{ paper.title }}]({{ paper.url | relative_url }})
{% endfor %}

## Presentations

{% for talk in site.talks reversed %}
- [{{ talk.title }}]({{ talk.url | relative_url }})
{% endfor %}

[XML sitemap]({{ '/sitemap.xml' | relative_url }})

---
layout: default
title:  "Scrumtuous Blog on Agile, Scrum & DevOps"
blurb: "Here are all of our tasty blog posts."
date:   2022-01-01 01:11:00 -0500
keywords: Scrumtuous Blog Agile DevOps AWS Certification Scrum
---

{% for post in site.posts %}			
<div style="border: 1px solid #DEDEDE;" class=" col-12 col-sm-12  col-md-6 col-lg-4 mb-1 mt-1">
<a href="{{ post.url }}">{{ post.title }}</a>
</div>
{% endfor %}

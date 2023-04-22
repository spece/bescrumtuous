---
layout: default
title:  "Scrumtuous Blog on Agile, Scrum & DevOps"
blurb: "Here are all of our tasty blog posts."
date:   2022-01-01 01:11:00 -0500
keywords: Scrumtuous Blog Agile DevOps AWS Certification Scrum
---
Hello!

{{ post.title }}


{% for post in site.posts %}			
abc
<a href="{{ post.url }}">{{ post.title }}</a>

{% endfor %}
 
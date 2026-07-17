---
layout: default
title: research
permalink: /research/
---

# Research

{% for paper in site.papers %}

[{{ paper.title }}]({{ paper.url }})\
{{ paper.authors }}\
*{{ paper.venue }}* | [link]({{ paper.paper_link }})\
{{ paper.tldr }} 

---

{% endfor %}
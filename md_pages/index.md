---
layout: default
title: César Guerra-Solano
permalink: /
---
# César Guerra-Solano
##### `guerrasolano[at]wisc[dot]edu` | [github](https://github.com/cgsol) | [google scholar](https://scholar.google.com/citations?user=0kk9zQsAAAAJ&hl=en) | [bluesky](https://bsky.app/profile/csrguerrasolano.bsky.social) | [twitter](https://x.com/csrguerrasolano)

<figure class="headshot">
  <img src="/assets/images/ireland_headshot.png"
      alt="An image of a man with dark hair and a blue sweater, with cliffs and water in the background.">
</figure>

My name is <b>César Guerra-Solano</b> -- I am a first-year PhD student in Computer Sciences at the [University of Wisconsin-Madison](https://www.wisc.edu)<img src="/assets/images/BuckyBadger.svg.png" class="text-icon">, supported by the NSF Graduate Research Fellowship. My research centers on natural language processing, computational social science, and computational sociolinguistics. I'm interested in understanding and improving user interaction & personalization, both for and using language technologies, with a focus on user diversity, safety, and augmentation.

In the past, I was an undergraduate at the [University of Pittsburgh](https://www.sci.pitt.edu)<img src="/assets/images/University_of_Pittsburgh_seal.svg" class="text-icon">. I graduated with a [Bachelor of Philosophy (BPhil)](https://www.frederickhonors.pitt.edu/academics/bachelor-philosophy-bphil-degree) in Computer Science & Computational Biology with a minor in Linguistics and was a [Stamps Scholar](https://www.stampsscholars.org). I defended a thesis, *Understanding LLM Adaptation to Diverse User Contexts*, advised by [Dr. Xiang Lorraine Li](https://lorraine333.github.io). I was also a [Chancellor's Undergraduate Teaching Fellow](https://www.frederickhonors.pitt.edu/research/research-creative-fellowships), which supported my work in making computational biology at Pitt more accessible. Throughout my time at Pitt, I was blessed to have incredible research and teaching mentors who motivated my interests in socially responsible language technologies and education -- Dr. Xiang Lorraine Li, [Dr. Michael Miller Yoder](https://michaelmilleryoder.github.io), and [Dr. Alex Maldonado](https://aalexmmaldonado.com).

I'm always happy to chat -- feel free to send me an email!

---

### Publications

{% assign selected = site.papers | where: "selected", true %}

{% for paper in selected %}
[{{ paper.title }}]({{ paper.url }})\
{{ paper.authors }}\
*{{ paper.venue }}* | [link]({{ paper.paper_link }})

---
{% endfor %}

[View all publications](/research/)

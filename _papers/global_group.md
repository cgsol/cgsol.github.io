---
title: "Think Globally, Group Locally: Evaluating LLMs Using Multi-Lingual Word Grouping Games"
authors: "<strong>César Guerra-Solano</strong>, Zhuochun Li, Xiang Lorraine Li"
venue: EMNLP Main 2025
selected: true
tldr: We design a flexible, resource-efficient multilingual abstract reasoning benchmark, and find LLM performance deficits related to language, cultural context, and domain.
paper_link: https://scholar.google.com/citations?view_op=view_citation&hl=en&user=0kk9zQsAAAAJ&citation_for_view=0kk9zQsAAAAJ:u5HHmVD_uO8C
---
**TL;DR**
{{ page.tldr }}

**Abstract**\
Large language models (LLMs) can exhibit biases in reasoning capabilities due to linguistic modality, performing better on tasks in one language versus another, even with similar content. Most previous works evaluate this through reasoning tasks where reliance on strategies or knowledge can ensure success, such as in commonsense or math tasks. However, abstract reasoning is vital to reasoning for everyday life, where people apply "out-of-the-box thinking" to identify and use patterns for solutions, without a reliance on formulaic approaches. Comparatively, little work has evaluated linguistic biases in this task type. In this paper, we propose a task inspired by the New York Times Connections: GlobalGroup, that evaluates models in an abstract reasoning task across several languages. We constructed a game benchmark with five linguistic backgrounds -- English, Spanish, Chinese, Hindi, and Arabic -- in both the native language and an English translation for comparison. We also proposed game difficulty measurements to evaluate models on games with similar difficulty, enabling a more controlled comparison, which is particularly important in reasoning evaluations. Through experimentation, we find English modalities largely lead to better performance in this abstract reasoning task, and performance disparities between open- and closed-source models.

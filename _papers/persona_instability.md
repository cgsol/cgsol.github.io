---
title: "Persona Non Grata: LLM Persona-Driven Generations in MCQA are Unstable in Distinct Dimensions"
authors: "<strong>César Guerra-Solano</strong>, Xiang Lorraine Li"
venue: Preprint. Under review.
selected: true
tldr: We design metrics to evaluate instability in persona-driven MCQA across three distinct dimensions, finding consistent patterns with hyperparameter type, choice, domain, and model performance. Importantly, these metrics can be used to inform future experiment design, even if used on a small batch of pilot data.
paper_link: https://arxiv.org/abs/2607.00937
---
**TL;DR**
{{ page.tldr }}

**Abstract**\
Persona-driven generations (PDGs) have seen prolific use in research and industry applications, where a large language model (LLM) takes on a 'persona' while completing some task. While persona expressed through free-form text (like dialogue) has substantial work investigating stability or consistency, relatively, persona expressed in non-text-heavy outputs (like in multiple-choice question answering, or MCQA) is often overlooked. We work to address this gap, seeking to understand the instability of LLM PDGs in MCQA tasks. We develop three metrics investigating the performance, outcome, and question correctness stability, evaluating three distinct dimensions. Using these metrics, we find that instability varies consistently between model families and model size, and across question domains, with math/commonsense questions leading to greater instability. We also find task prompt format introduces more prediction instability than other hyperparameters, like temperature. Finally, we find that instability is related to task accuracy, and using our instability metrics, find different experimental settings that result in different best and worst personas for tasks, despite their similarity. This reveals the importance of checking hyperparameter instability in PDGs.
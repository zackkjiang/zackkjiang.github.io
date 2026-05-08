---
layout: page
title: ECAG2
description: A multi-agent AI framework for ECG interpretation across diverse cardiac scenarios.
img: assets/img/projects/ecag2.jpg
importance: 4
category: Cardiac Monitoring
related_publications: false
github: https://github.com/zack1111111111111/ECAG2
youtube:
devpost:
website: https://ecag2.netlify.app/
---

## Motivation

Modern ECG interpretation is rarely a single act of pattern recognition — it's a layered reasoning process across rhythm, morphology, ischemia, and patient context that human cardiologists do almost effortlessly but that single end-to-end models still struggle to make transparent. ECAG2 explores whether a society of specialized AI agents, each focused on one diagnostic dimension, can collaborate to deliver explainable cardiac reasoning.

## How it works

The framework decomposes ECG analysis into specialist agents — each responsible for a focused subdomain such as arrhythmia detection, morphological analysis, or scenario-specific pattern recognition — that share a common signal-processing backbone and coordinate through a structured tool layer. Together they reason over a curated library of ECG scenarios, producing both a diagnostic conclusion and a traceable account of how the conclusion was reached.

{% if page.youtube or page.devpost or page.github or page.website %}

## Links

<div class="project-links">
{% if page.youtube %}<a class="btn btn-sm btn-outline-danger" href="{{ page.youtube }}" target="_blank" rel="noopener">▶ Watch on YouTube</a>{% endif %}
{% if page.devpost %}<a class="btn btn-sm btn-outline-info" href="{{ page.devpost }}" target="_blank" rel="noopener">View on Devpost</a>{% endif %}
{% if page.github %}<a class="btn btn-sm btn-outline-dark" href="{{ page.github }}" target="_blank" rel="noopener">GitHub Repository</a>{% endif %}
{% if page.website %}<a class="btn btn-sm btn-outline-success" href="{{ page.website }}" target="_blank" rel="noopener">🌐 Live Demo</a>{% endif %}
</div>

{% endif %}

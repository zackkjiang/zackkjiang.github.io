---
layout: page
title: Heartup
description: Wearable cardiac sensing platform for continuous, ambient heart-health monitoring.
img: assets/img/projects/heartup.jpg
importance: 1
category: Cardiac Monitoring
related_publications: false
github:
youtube: https://www.youtube.com/watch?v=5koxoWdBqBc
devpost:
website:
---

## Motivation

Most cardiac events that send people to the hospital were preceded by days, sometimes weeks, of subtle physiological signals that no one was watching. Heartup is built on the premise that meaningful heart-health monitoring should fade into daily life — soft enough to wear, smart enough to flag what matters, quiet enough to stay out of the way.

## How it works

The platform combines flexible electrode and accelerometer-based sensors with on-device biosignal processing for ECG and seismocardiography (SCG). Continuous waveforms are denoised and feature-extracted in real time, then routed to lightweight ML models that detect rhythm anomalies, inter-beat variability shifts, and mechanical contraction abnormalities — surfacing only the events that warrant clinical attention.

{% if page.youtube or page.devpost or page.github or page.website %}

## Links

<div class="project-links">
{% if page.youtube %}<a class="btn btn-sm btn-outline-danger" href="{{ page.youtube }}" target="_blank" rel="noopener">▶ Watch on YouTube</a>{% endif %}
{% if page.devpost %}<a class="btn btn-sm btn-outline-info" href="{{ page.devpost }}" target="_blank" rel="noopener">View on Devpost</a>{% endif %}
{% if page.github %}<a class="btn btn-sm btn-outline-dark" href="{{ page.github }}" target="_blank" rel="noopener">GitHub Repository</a>{% endif %}
{% if page.website %}<a class="btn btn-sm btn-outline-success" href="{{ page.website }}" target="_blank" rel="noopener">🌐 Live Demo</a>{% endif %}
</div>

{% endif %}

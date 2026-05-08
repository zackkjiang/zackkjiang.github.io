---
layout: page
title: Claudiac
description: An AI-powered platform that turns real-time heartbeat data into emotional connection for remote loved ones.
img: assets/img/projects/claudiac.jpg
importance: 3
category: Cardiac Monitoring
related_publications: false
github:
youtube:
devpost: https://devpost.com/software/claudiac
website:
---

## Motivation

Heart-rate monitors are usually built for clinicians, not for the people who love the wearer. Claudiac asks a different question: what if a heartbeat could travel between two phones the way a text message does — what if a parent half a world away could feel, not just see, that their child was okay tonight?

## How it works

A wearable cardiac sensor streams real-time heartbeat waveforms to a paired mobile app, where the signal is rendered as ambient haptic, visual, and audio feedback for chosen recipients. An on-device AI layer interprets longer-term rhythm and variability patterns, surfacing context — calm, excited, asleep, stressed — so that a remote loved one experiences not raw data but presence, in a form that is private, gentle, and emotionally legible.

{% if page.youtube or page.devpost or page.github or page.website %}

## Links

<div class="project-links">
{% if page.youtube %}<a class="btn btn-sm btn-outline-danger" href="{{ page.youtube }}" target="_blank" rel="noopener">▶ Watch on YouTube</a>{% endif %}
{% if page.devpost %}<a class="btn btn-sm btn-outline-info" href="{{ page.devpost }}" target="_blank" rel="noopener">View on Devpost</a>{% endif %}
{% if page.github %}<a class="btn btn-sm btn-outline-dark" href="{{ page.github }}" target="_blank" rel="noopener">GitHub Repository</a>{% endif %}
{% if page.website %}<a class="btn btn-sm btn-outline-success" href="{{ page.website }}" target="_blank" rel="noopener">🌐 Live Demo</a>{% endif %}
</div>

{% endif %}

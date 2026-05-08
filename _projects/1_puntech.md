---
layout: page
title: Puntech
description: AI-powered VR boxing training partner with flexible impact sensors.
img: assets/img/projects/puntech.jpg
importance: 1
category: Sport Interface
related_publications: false
github:
youtube:
devpost: https://devpost.com/software/puntech
website:
---

## Motivation

Boxing training has always relied on a coach standing across from you, a heavy bag, or a partner — none of which are available 24/7, and none of which can quantify what just happened in the last three seconds. Puntech reimagines the heavy bag as a sensor-instrumented, voice-interactive partner that can spar with you, count your shots, and adapt the workout in real time.

## How it works

Flexible piezoelectric and triboelectric sensors are embedded across the impact surface of a VR-paired training pad, capturing the location, force, and timing of every strike. The signals stream to an on-device AI agent that classifies punch type (jab / cross / hook / uppercut), evaluates technique, and responds with adaptive verbal coaching through a conversational voice interface — turning a passive bag into an active sparring partner.

{% if page.youtube or page.devpost or page.github or page.website %}

## Links

<div class="project-links">
{% if page.youtube %}<a class="btn btn-sm btn-outline-danger" href="{{ page.youtube }}" target="_blank" rel="noopener">▶ Watch on YouTube</a>{% endif %}
{% if page.devpost %}<a class="btn btn-sm btn-outline-info" href="{{ page.devpost }}" target="_blank" rel="noopener">View on Devpost</a>{% endif %}
{% if page.github %}<a class="btn btn-sm btn-outline-dark" href="{{ page.github }}" target="_blank" rel="noopener">GitHub Repository</a>{% endif %}
{% if page.website %}<a class="btn btn-sm btn-outline-success" href="{{ page.website }}" target="_blank" rel="noopener">🌐 Live Demo</a>{% endif %}
</div>

{% endif %}

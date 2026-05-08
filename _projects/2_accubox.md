---
layout: page
title: AccuBox
description: Intelligent boxing helmet with real-time punch detection and live AI sportscaster commentary.
img: assets/img/projects/accubox.jpg
importance: 2
category: Sport Interface
related_publications: false
github:
youtube:
devpost: https://devpost.com/software/bocracu
website:
---

## Motivation

Combat sports generate some of the most expressive biomechanical events in athletics, yet the data layer around them is almost non-existent — fighters and coaches still rely on slow-motion replays and gut feel to judge what happened. AccuBox closes that gap by turning protective gear itself into an instrumented, broadcast-aware sensing system.

## How it works

A dense array of impact-sensitive flexible sensors is integrated into the boxing helmet shell, detecting punch location, force, and accumulated head exposure in real time. The on-device pipeline classifies hit type and intensity, then feeds the event stream into a conversational voice agent that delivers live, sportscaster-style commentary — the helmet effectively narrates its own fight while logging objective impact metrics for safety analysis afterward.

{% if page.youtube or page.devpost or page.github or page.website %}

## Links

<div class="project-links">
{% if page.youtube %}<a class="btn btn-sm btn-outline-danger" href="{{ page.youtube }}" target="_blank" rel="noopener">▶ Watch on YouTube</a>{% endif %}
{% if page.devpost %}<a class="btn btn-sm btn-outline-info" href="{{ page.devpost }}" target="_blank" rel="noopener">View on Devpost</a>{% endif %}
{% if page.github %}<a class="btn btn-sm btn-outline-dark" href="{{ page.github }}" target="_blank" rel="noopener">GitHub Repository</a>{% endif %}
{% if page.website %}<a class="btn btn-sm btn-outline-success" href="{{ page.website }}" target="_blank" rel="noopener">🌐 Live Demo</a>{% endif %}
</div>

{% endif %}

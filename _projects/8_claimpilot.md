---
layout: page
title: ClAImPilot
description: An AI-powered dashcam assistant that helps non-English-speaking drivers handle accidents through multilingual voice guidance, automated reporting, and insurance claim support.
img: assets/img/projects/claimpilot.jpg
importance: 1
category: Dashcam AI
related_publications: false
github:
youtube:
devpost: https://devpost.com/software/claimpilot-i138sf
website:
---

## Motivation

A car accident is already one of the worst minutes of someone's life. For a driver who speaks limited English, the next hour — explaining what happened to police, exchanging information, opening an insurance claim — can be just as costly as the crash itself. ClAImPilot is built for that hour.

## How it works

A vision-language model continuously analyzes the dashcam feed, detects collision events, and reconstructs what occurred from the moments before and after impact. When an incident is confirmed, a multilingual voice agent walks the driver through what to do next — what to photograph, what to say, what to ask the other party — in their native language, then auto-generates a structured incident report and a claim package ready to submit to their insurance provider.

{% if page.youtube or page.devpost or page.github or page.website %}

## Links

<div class="project-links">
{% if page.youtube %}<a class="btn btn-sm btn-outline-danger" href="{{ page.youtube }}" target="_blank" rel="noopener">▶ Watch on YouTube</a>{% endif %}
{% if page.devpost %}<a class="btn btn-sm btn-outline-info" href="{{ page.devpost }}" target="_blank" rel="noopener">View on Devpost</a>{% endif %}
{% if page.github %}<a class="btn btn-sm btn-outline-dark" href="{{ page.github }}" target="_blank" rel="noopener">GitHub Repository</a>{% endif %}
{% if page.website %}<a class="btn btn-sm btn-outline-success" href="{{ page.website }}" target="_blank" rel="noopener">🌐 Live Demo</a>{% endif %}
</div>

{% endif %}

---
layout: page
title: Yogoddess
description: An AI-powered smart yoga assistant using biosignal sensors to monitor focus, muscle activity, and stress for safer, more mindful practice.
img: assets/img/projects/yogoddess.jpg
importance: 1
category: Rehabilitation
related_publications: false
github:
youtube:
devpost: https://devpost.com/software/xxx-s3ymup
website:
---

## Motivation

Yoga is a practice of deep internal attention — yet the moment you start watching your form in a mirror, you've already left the practice. Yogoddess offers an alternative observer: a sensing layer that quietly tracks what your body and mind are doing, so you don't have to.

## How it works

Wearable EMG and physiological sensors capture muscle activation patterns, breathing rhythm, and autonomic indicators of stress and focus throughout a session. The on-device AI agent maps these signals onto pose-specific expectations — flagging compensations, asymmetries, or signs of strain in real time — and delivers gentle, voice-based feedback that helps the practitioner refine alignment without breaking concentration.

{% if page.youtube or page.devpost or page.github or page.website %}

## Links

<div class="project-links">
{% if page.youtube %}<a class="btn btn-sm btn-outline-danger" href="{{ page.youtube }}" target="_blank" rel="noopener">▶ Watch on YouTube</a>{% endif %}
{% if page.devpost %}<a class="btn btn-sm btn-outline-info" href="{{ page.devpost }}" target="_blank" rel="noopener">View on Devpost</a>{% endif %}
{% if page.github %}<a class="btn btn-sm btn-outline-dark" href="{{ page.github }}" target="_blank" rel="noopener">GitHub Repository</a>{% endif %}
{% if page.website %}<a class="btn btn-sm btn-outline-success" href="{{ page.website }}" target="_blank" rel="noopener">🌐 Live Demo</a>{% endif %}
</div>

{% endif %}

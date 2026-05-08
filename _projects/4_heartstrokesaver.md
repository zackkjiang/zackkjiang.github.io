---
layout: page
title: HeartStrokeSaver
description: Real-time CPR monitoring system with an AI voice assistant that evaluates compression quality during resuscitation.
img: assets/img/projects/heartstrokesaver.jpg
importance: 2
category: Cardiac Monitoring
related_publications: false
github:
youtube:
devpost: https://devpost.com/software/heartstrokesaver
website:
---

## Motivation

Survival from out-of-hospital cardiac arrest hinges on the quality of CPR delivered in the first ten minutes — yet bystanders, and even trained responders under stress, routinely deliver compressions at the wrong rate, depth, or recoil. HeartStrokeSaver brings a calm, knowledgeable voice into the scene, in real time.

## How it works

A wearable sensing module captures chest compression depth and rate alongside the patient's cardiac response. Signals are processed on-device and translated into actionable cues by a conversational voice agent — telling the rescuer when to push harder, slow down, allow recoil, or rotate compressors — while logging objective resuscitation metrics for post-event review and EMS handoff.

{% if page.youtube or page.devpost or page.github or page.website %}

## Links

<div class="project-links">
{% if page.youtube %}<a class="btn btn-sm btn-outline-danger" href="{{ page.youtube }}" target="_blank" rel="noopener">▶ Watch on YouTube</a>{% endif %}
{% if page.devpost %}<a class="btn btn-sm btn-outline-info" href="{{ page.devpost }}" target="_blank" rel="noopener">View on Devpost</a>{% endif %}
{% if page.github %}<a class="btn btn-sm btn-outline-dark" href="{{ page.github }}" target="_blank" rel="noopener">GitHub Repository</a>{% endif %}
{% if page.website %}<a class="btn btn-sm btn-outline-success" href="{{ page.website }}" target="_blank" rel="noopener">🌐 Live Demo</a>{% endif %}
</div>

{% endif %}

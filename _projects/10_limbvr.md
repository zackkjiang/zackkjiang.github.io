---
layout: page
title: LimbVR
description: An AI-assisted VR rehabilitation platform that uses biosignals and real-time sensor feedback to help amputees train prosthetic control through immersive virtual interaction.
img: assets/img/projects/limbvr.jpg
importance: 2
category: Rehabilitation
related_publications: false
github:
youtube:
devpost: https://devpost.com/software/cybathlon-vr
website:
---

## Motivation

Learning to control a prosthetic limb is, at its core, a relearning of intention — the brain must rewire how it sends commands and how it interprets the absence of native feedback. Conventional rehabilitation is slow, repetitive, and sterile. LimbVR replaces the rehabilitation room with a virtual world that is engaging, infinitely reconfigurable, and instrumented down to the individual muscle fiber.

## How it works

EMG sensors on the residual limb decode user intent, while a gravity-loading simulation framework reproduces the physical resistance the user would feel from a real prosthesis interacting with objects. Inside an immersive VR environment, patients perform progressively challenging tasks — grasping, reaching, transferring weight — and the AI layer adapts difficulty in real time based on muscle effort, accuracy, and fatigue, producing a rehabilitation curve that is both faster and more measurable than conventional protocols.

{% if page.youtube or page.devpost or page.github or page.website %}

## Links

<div class="project-links">
{% if page.youtube %}<a class="btn btn-sm btn-outline-danger" href="{{ page.youtube }}" target="_blank" rel="noopener">▶ Watch on YouTube</a>{% endif %}
{% if page.devpost %}<a class="btn btn-sm btn-outline-info" href="{{ page.devpost }}" target="_blank" rel="noopener">View on Devpost</a>{% endif %}
{% if page.github %}<a class="btn btn-sm btn-outline-dark" href="{{ page.github }}" target="_blank" rel="noopener">GitHub Repository</a>{% endif %}
{% if page.website %}<a class="btn btn-sm btn-outline-success" href="{{ page.website }}" target="_blank" rel="noopener">🌐 Live Demo</a>{% endif %}
</div>

{% endif %}

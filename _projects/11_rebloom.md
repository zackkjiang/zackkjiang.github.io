---
layout: page
title: ReBloom
description: An AI-powered AR postpartum recovery coach that uses EMG biosignals and real-time feedback to help mothers safely rebuild core strength.
img: assets/img/projects/rebloom.jpg
importance: 3
category: Rehabilitation
related_publications: false
github:
youtube:
devpost: https://devpost.com/software/rebloom
website:
---

## Motivation

Postpartum recovery is one of the most underserved domains in modern healthcare — millions of mothers are sent home with a single pamphlet and the vague suggestion to "do some Kegels." Diastasis recti, pelvic floor dysfunction, and core instability go undiagnosed and unaddressed for years. ReBloom is built to give postpartum recovery the precision, personalization, and patience it has always deserved.

## How it works

Soft EMG sensors monitor pelvic floor and deep core activation in real time, while an AR overlay guides the user through anatomically-correct exercise progressions on her phone or tablet. An AI coaching agent interprets the muscle signals, adapts the program to the user's current recovery stage, and provides gentle, real-time corrections — ensuring that each rep is doing what it's supposed to do, and that progression is grounded in the body's actual readiness rather than calendar weeks postpartum.

{% if page.youtube or page.devpost or page.github or page.website %}

## Links

<div class="project-links">
{% if page.youtube %}<a class="btn btn-sm btn-outline-danger" href="{{ page.youtube }}" target="_blank" rel="noopener">▶ Watch on YouTube</a>{% endif %}
{% if page.devpost %}<a class="btn btn-sm btn-outline-info" href="{{ page.devpost }}" target="_blank" rel="noopener">View on Devpost</a>{% endif %}
{% if page.github %}<a class="btn btn-sm btn-outline-dark" href="{{ page.github }}" target="_blank" rel="noopener">GitHub Repository</a>{% endif %}
{% if page.website %}<a class="btn btn-sm btn-outline-success" href="{{ page.website }}" target="_blank" rel="noopener">🌐 Live Demo</a>{% endif %}
</div>

{% endif %}

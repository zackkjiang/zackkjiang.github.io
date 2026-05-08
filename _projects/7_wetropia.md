---
layout: page
title: WeTropia
description: An AI agent platform for personalized everyday well-being.
img: assets/img/projects/wetropia.jpg
importance: 1
category: AI Agent
related_publications: false
github: https://github.com/MineSelf2016/women_health_agent
youtube: https://youtu.be/GsCxi1k11Tg
youtube2: https://youtu.be/2HXclM2FFwQ
devpost:
website:
---

## Motivation

People don't lack information about how to live better — they lack a patient, attentive companion that knows their context and shows up at the right moment. WeTropia is an attempt at that companion: not a chatbot, not a tracker, but an agent that quietly understands the rhythm of a person's life and helps them move toward the version of themselves they actually want to be.

## How it works

WeTropia is built as a multi-agent system in which specialized agents handle different domains of daily life — sleep, movement, focus, recovery, social presence — and a coordinator agent decides what is worth surfacing, when, and in what tone. The platform integrates with biosignal and behavioral data sources, reasons across them, and delivers personalized interventions through a conversational interface designed to feel like a thoughtful friend rather than a productivity tool.

{% if page.youtube or page.youtube2 or page.devpost or page.github or page.website %}

## Links

<div class="project-links">
{% if page.youtube %}<a class="btn btn-sm btn-outline-danger" href="{{ page.youtube }}" target="_blank" rel="noopener">▶ Hack Demo Video</a>{% endif %}
{% if page.youtube2 %}<a class="btn btn-sm btn-outline-danger" href="{{ page.youtube2 }}" target="_blank" rel="noopener">▶ Final Pitch Video</a>{% endif %}
{% if page.devpost %}<a class="btn btn-sm btn-outline-info" href="{{ page.devpost }}" target="_blank" rel="noopener">View on Devpost</a>{% endif %}
{% if page.github %}<a class="btn btn-sm btn-outline-dark" href="{{ page.github }}" target="_blank" rel="noopener">GitHub Repository</a>{% endif %}
{% if page.website %}<a class="btn btn-sm btn-outline-success" href="{{ page.website }}" target="_blank" rel="noopener">🌐 Live Demo</a>{% endif %}
</div>

{% endif %}

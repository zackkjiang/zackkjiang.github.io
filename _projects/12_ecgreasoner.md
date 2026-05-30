---
layout: page
title: ECG Reasoner
description: Explainable wearable cardiac monitoring that pairs deterministic ECG signal processing with multi-agent clinical reasoning under the OpenClaw safety harness.
img: assets/img/projects/ecgreasoner.jpg
importance: 5
category: Cardiac Monitoring
related_publications: false
---

## Motivation

Large language models are starting to reason about clinical data, but in cardiology a confident-sounding wrong answer is not a harmless one. Most medical AI systems remain hard to interpret, weakly grounded in actual physiology, and difficult to trust in high-risk settings. ECG Reasoner takes the opposite stance: every diagnosis must be traceable to a specific physiological measurement, every uncertain case must fail conservatively, and the whole thing must run on hardware a person already owns — a watch, a laptop, and a safety layer in between.

## How it works

ECG waveforms are captured from a consumer wearable such as an Apple Watch and passed through a deterministic DSP layer built on the classical Pan–Tompkins QRS detection algorithm — bandpass filtering, derivative enhancement, squaring, moving-window integration, and adaptive thresholding — for transparent, reproducible R-peak localization without any black-box inference. From the detected beats the system extracts an interpretable feature bundle: heart rate, heart rate variability (HRV/SDNN), RR-interval variability, ectopic-beat ratio, and R-peak amplitude.

A rule-based arrhythmia classifier first normalizes these features into safety-oriented risk categories (normal, watch, concern, critical) before any LLM is involved. The structured features then go to an AG2 multi-agent consultation, where a *SignalAnalyst* agent proposes ranked diagnostic hypotheses and a *Cardiologist* agent commits to a single diagnosis — with every conclusion required to cite explicit feature values. Wrapping the entire reasoning layer is **OpenClaw**, a safety harness enforcing output guardrails, evidence verification, consistency checks, conservative fallback policies, and audit logging. The final output is an evidence-grounded diagnosis delivered in dual modes: a technical clinician view and a plain-language patient view.

## Demo

*End-to-end demonstration video coming soon.*

## Funding &amp; recognition

🏆 **2nd Place Award — CVPR 2026 Workshop, GigaBrain Challenge (PhysClaw Track)**, Denver, CO, June 2026.

Awarded to Team **OpenClaw CardioHarness**: Zhipeng Jiang, Xinyu Zhang, Hanzhang Fang, Jing Huang, Ying Zhou.

## Collaborators

A cross-institution effort across New Jersey Institute of Technology, Indiana University Bloomington, and Georgia Institute of Technology. Developed in part at the [Dong Lab](https://centers.njit.edu/donglab/), New Jersey Institute of Technology.

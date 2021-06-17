---
description: >-
  We set up central repositories for our design system artifacts and establish a
  steady flow of components and optimizations between them.
---

# Steady Flow of Truth

**Single Source of Truth** is a key concept of design systems. It describes the practice of structuring information such that every individual element is stored and edited in only one place. A SSOT helps to prevent redundancies and unwanted variances and can be called upon to settle disputes. Depending on an organization's goals and background, their SSOT for design components might be a code repository, a documented set of guidelines or a comprehensive UI kit \(built and maintained in tools like Figma or Adobe XD\). Being able to rely on a Single Source of Truth when designing and developing digital products in teams is critical for avoiding the accumulation of technical and design debt. 

Lean Design System proposes a more flexible approach to this concept. Instead of having one Single Source of Truth, we establish a steady flow of new components and optimizations populating our repositories. In this way, we aim to achieve several things:

* We aim to **foster cross-functional design and development processes** to better understand our respective struggles and establish collective ownership to break up knowledge silos.
* We aim to **promote exploration and continuous optimization**.
* We aim to **avoid building and validating unrealistic prototypes** that do not adequately reflect the actual capabilities of our technology in order to save us time and frustration.

{% hint style="warning" %}
It should be noted that Steady Flow of Truth heavily relies on [Design Codification](../principles/design-codification.md) to work as intended. If we're certain that we don't want to adopt Design Codification for our design system, we might have to make adjustments or skip this tactic altogether.
{% endhint %}

The following diagram \(fig. 1\) outlines how the stream of development ideally populates the different repositories of our design system, as well as each station's role in the process. Let's go through them one by one.

![Fig. 1: Steady Flow of Truth](../../.gitbook/assets/fig_steady_flow.svg)

## Code Repository


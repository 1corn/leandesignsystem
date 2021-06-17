---
description: >-
  We set up central repositories for our design system artifacts and establish a
  steady flow of components and optimizations between them.
---

# Steady Flow of Truth

**Single Source of Truth** is a key concept of design systems. It describes the practice of structuring information such that every individual element is stored and edited in only one place. A SSOT helps to prevent redundancies and unwanted variances and can be called upon to settle disputes. Depending on an organization's goals and background, their SSOT for design components might be a code repository, a documented set of guidelines, or a comprehensive UI kit \(built and maintained in tools like Figma or Adobe XD\). Being able to rely on a Single Source of Truth when designing and developing digital products in teams is critical for avoiding the accumulation of technical and design debt. 

Lean Design System proposes a more flexible approach to this concept. Instead of having one Single Source of Truth, we establish a steady flow of new components and optimizations populating several semi-independent repositories. In this way, we aim to:

* ... **foster cross-functional design and development processes** to better understand our respective struggles and establish collective ownership to break down information silos.
* ... **promote exploration and continuous optimization**.
* ... **avoid building and validating unrealistic prototypes** that do not adequately reflect the actual capabilities of our technology in order to save us time and frustration.

{% hint style="warning" %}
It should be noted that **Steady Flow of Truth** heavily relies on [Design Codification](../principles/design-codification.md) to work as intended. If we're certain that we don't want to adopt [Design Codification](../principles/design-codification.md) for our design system, we might have to make adjustments or skip this tactic altogether.
{% endhint %}

The following diagram \(fig. 1\) outlines how the stream of development ideally populates the different repositories of our design system, as well as each station's role in the process. But let's go through them one by one.

![Fig. 1: Steady Flow of Truth](../../.gitbook/assets/fig_steady_flow.svg)

## Code Repository

The Lean Design System methodology strongly promotes to adopt the principle of [Design Codification](../principles/design-codification.md). [Design Codification](../principles/design-codification.md), if done right, enables teams to collaborate much more naturally and empowers designers by providing them with powerful levers. This is why we should make our design system's code repository our main repository. Whatever is defined in the code repository should always represent the ultimate truth. However, we don't necessarily need a comprehensive component library right away. The concept of [Design Tokens](../artifacts/design-tokens.md) \(and the tactic of the same name\) is a great place to start the process of [Design Codification](../principles/design-codification.md). [Design Tokens](../artifacts/design-tokens.md) allow us to codify our UI components step by step and layer by layer. [On the Shoulders of Giants](on-the-shoulders-of-giants.md) proposes a flexible UI architecture that utilizes 3rd party front-end frameworks to help us with some of the heavy lifting in building digital products. Both concepts are also compatible with the Utility-first approach as pioneered by the talented people at [Tailwind CSS](https://tailwindcss.com/docs/utility-first).

## UI Kit

Our [UI Kit](../artifacts/ui-kits.md) lives in a modern UI design tool such as Figma, Adobe XD or Sketch. While some of these provide ways to generate code automatically, the corresponding workflows can make us too dependent on a specific tool or framework. Also, the code quality may not be up to scratch, as there are semantic gaps that still prove hard to bridge from this side of the handoff process. Instead, Lean Design System promotes the adoption of [Design Tokens](../artifacts/design-tokens.md) as a much more effective and fluent approach to the integration of design and development efforts. For that reason \(and as we can see in fig. 1\), the [UI Kit](../artifacts/ui-kits.md) should always be based on the latest definitions in our code repository. In other words, we basically _trace_ actual components exactly as they are rendered on screen. What may seem a bit cumbersome at first will ensure that the UI Kit never takes the lead over the code repository.


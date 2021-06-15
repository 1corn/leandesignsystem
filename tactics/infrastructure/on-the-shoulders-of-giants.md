---
description: >-
  We leverage external resources to their fullest without exposing ourselves to
  avoidable risks and dependencies.
---

# On the Shoulders of Giants

[Minimum Viable Design System](../principles/minimum-viable-design-system.md) promotes the systematic exploitation of external resources in order to make a design system and its components usable as soon as possible. Depending on our specific requirements and goals, such resources might include all kinds of open source projects, modern front-end frameworks, or asset libraries \(icon sets, font families, etc.\). However, relying heavily on a resource that is not under our direct control exposes us to some risks that need to be considered: The dependency on a specific resource can severely compromise our flexibility. We're at the mercy of external teams when it comes to future developments. Radical changes might require us to adapt our own implementations accordingly and the abandonment of a project or the discontinuation of vital features might even force us to jump ship entirely and look for alternatives.

On the Shoulders of Giants proposes guidelines on a sustainable approach to utilizing external resources—with the goal to minimize potential risks and maximize the benefits. It is based on two core ideas:

* Use as intended
* Keep interfaces clean

![Fig. 1: Front-end architecture, product view](../../.gitbook/assets/fig_architecture_product.svg)

If we zoom out a little and , we can see that such an architecture can work for a diverse product portfolio and different implementations can all draw from the same design tokens foundation—so long as we keep our interfaces clean and simple and utilize the provided theming capabilities as they were intended. This is an extremely powerful paradigm that even allows us to explore different approaches for different platforms.

![Fig. 2: Front-end architecture, platform view](../../.gitbook/assets/fig_architecture_platform.svg)


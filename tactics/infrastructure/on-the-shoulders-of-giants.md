---
description: >-
  We leverage 3rd party resources to their fullest and steer clear of common
  pitfalls.
---

# On the Shoulders of Giants

[Minimum Viable Design System](../principles/minimum-viable-design-system.md) promotes the systematic exploitation of 3rd party resources with the goal to make a design system and its components usable as soon as possible. Depending on our specific requirements and objectives, such resources might include all kinds of open source projects, modern front-end frameworks, or asset libraries \(icon sets, font families, etc.\). However, relying heavily on anything that is not under our direct control exposes us to some risks that need to be considered: The dependency on a specific resource can severely compromise our flexibility. We're at the mercy of external teams when it comes to future developments. Radical changes might require us to adapt our own implementations accordingly and the abandonment of a project or the discontinuation of vital features might even force us to jump ship entirely and look for alternatives.

On the Shoulders of Giants proposes guidelines around the sustainable integration of external resources—with the aim to minimize potential risks and maximize the benefits. It is based on two core ideas:

* **Use as intended:** When importing an external resource into our system, we should exercise due diligence and try to understand its underlying concepts first, so that we can use it exactly as intended.
* **Clean interfaces:** By keeping all interfaces between our own implementations and external resources as clean and simple as possible, we preserve our flexibility and avoid becoming overly dependent.

Implementing these ideas can be difficult at times, but it's almost certainly worth the extra effort. And once practiced regularly, chances are it will become a habit to follow the Giant's paradigm.

## Use as intended

By respecting an external project's ideas and underlying concepts, and by following its rules and guidelines, we are able to achieve several things:

1. Updates can be performed quickly and smoothly.
2. Existing project documentation remains valid and can be referenced in our own documentation
3. Especially in the case of well-known, established frameworks and projects, we can rely on a community for support and inspiration.
4. In the same vein, new designers and developers may already have prior experience with a certain project or framework, resulting in an easier onboarding process.

## Clean interfaces

Keeping the interfaces between our own implementations and external frameworks clean and simple will make it easier to swap them for alternatives at a later point in time. It reduces our dependencies and with that, the risks associated with backing the wrong horse or dragging along legacy projects.

Consider the following \(very simple\) web development example: If we're using a CSS reset in our project and need to make some adjustments for it to work properly in our context, we should avoid touching the original source file. Instead, we should set up a separate CSS file \(or an SCSS partial\) that handles all overrides applied to 3rd party frameworks and define our changes there. This allows us to easily and safely update the CSS reset in the future—and even after replacing it with an alternative at some point, we might still be able to reuse our separately stored overrides.

The next example is slightly more complex, but also much more powerful. The illustration below \(fig. 1\) shows a flexible front-end architecture based on a [Design Tokens](../artifacts/design-tokens.md) foundation. [Design Tokens](../artifacts/design-tokens.md) are codified design attributes that can be defined, understood and applied by developers and designers alike. In this example, a 3rd party front-end framework \(like [Material-UI](https://material-ui.com/)\) is used to render all layouts and widgets for an app or a website. Below this layer, all visual attributes related to our brand design language are stored in a central [Design Tokens](../artifacts/design-tokens.md) repository. We use the 3rd party framework's native theming capabilities to pull all relevant values from the tokens layer and by that, apply our distinctive look and feel to the product we're building. Above the framework layer, another separate layer handles custom overrides and the definitions of additional elements—basically everything that goes beyond the framework's capabilities.

![Fig. 1: Front-end architecture, product view](../../.gitbook/assets/fig_architecture_product.svg)

If we zoom out a little further \(fig. 2\), we can see that an architecture as outlined above can easily stretch across a diverse product portfolio. Here, four different implementations all draw from the same [Design Tokens](../artifacts/design-tokens.md) foundation. The result is a heterogeneous environment in which everything still originates from the same DNA. Changes on the [Design Tokens](../artifacts/design-tokens.md) layer propagate upwards, producing design consistency without stifling flexibility. We're free to explore different frameworks and approaches for different use-cases, making this architecture highly versatile and ideally suited for fast-moving teams and organizations.

![Fig. 2: Front-end architecture, platform view](../../.gitbook/assets/fig_architecture_platform.svg)

## Workflows over tools

The idea of minimizing external dependencies also extends to our tooling. We should focus on the goals we set and the workflows that get us there, rather than the underlying tools and technologies we're utilizing. By staying flexible and not becoming too dependent, we enable ourselves to always adopt the ideal tooling for a specific problem. A technology-agnostic approach like this promotes continued exploration and protects us from getting locked into a paradigm or platform that, at some point, may no longer serve our goals.

## Where this tactic fits in

{% tabs %}
{% tab title="🙏  This tactic benefits from" %}
Constantly reviewing and refactoring our implementations will lead to cleaner and simpler interfaces between the building blocks of our design system.

{% page-ref page="../actions/clean-up.md" %}

Design Tokens provide ways to keep the interfaces between our technical implementations clean and simple.

{% page-ref page="../artifacts/design-tokens.md" %}
{% endtab %}

{% tab title="💪  This tactic supports" %}
Keeping the interfaces between our own implementations and 3rd party resources clean will help us stay flexible and mitigate unwanted risks and dependencies.

{% page-ref page="../principles/minimum-viable-design-system.md" %}
{% endtab %}
{% endtabs %}

#### Authors and contributors

D. Kurfess


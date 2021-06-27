---
description: >-
  We consolidate our component designs in one central place to enable effortless
  exploration and prototyping.
---

# UI Kit

When we analyze the visual anatomy of today's most popular apps, we can observe a very high degree of consistency, making them feel polished, easy to navigate, and generally pleasant to interact with. Besides the consistent use of typography and color, we might find that the same paddings are applied to cards, forms, and menus, that the proportions of modules are affected similarly by viewport changes, and that animations all follow the same set of rules. To ensure the correct application of patterns and attributes defined by an underlying design language, digital product teams use standardized component libraries for their design work. Typically, these libraries contain modular building blocks, plus all relevant guidelines specifying nesting and recombination options. Increasingly, these libraries are referred to as UI Kits and are maintained in modern design tools such as Figma, Adobe XD, or Sketch.

## The UI Kit in the context of Lean Design System

UI Kits are powerful tools and in the context of Lean Design System methodology, they play a vital role in cross-functional communication. They also enable effortless design exploration and prototyping. Before we take a look at an ideal design system stream, we internalize the following general guidelines on how to maintain an effective UI Kit:

* Elements in our UI Kit should be structured and organized in a way that helps its users to apply the components correctly and effortlessly. [Brad Frost's Atomic Design](https://bradfrost.com/blog/post/atomic-web-design/) methodology outlines a reliable and battle-tested model for this and should, by now, almost be considered required reading for anyone working on digital products.
* Our UI Kit should be kept clean and free of redundancies. Elements should be defined carefully and precisely, as every deficiency in our standard components will inevitably multiply over time and ripple into our project work. See also: [Tidy up!](../actions/clean-up.md)
* If possible, we should organize all our standard components in one shared file that should be considered the reference for all prototyping and exploration work. If we, for whatever reason, require a structure of multiple files, we should make sure repeating components are either linked directly or only defined in one of the files to avoid repetitive update work and potential discrepancies.

> The consolidation of components in one central place makes it much easier to knock out consistent prototypes and represents a safe haven to return to from our visual explorations.

In case we decide to adopt [Design Codification](../principles/design-codification.md) and establish a [Steady Flow of Truth](../infrastructure/steady-flow-of-truth.md) through our libraries, our code repository will provide the basis for all components in our UI Kit. In other words, we quite literally trace components exactly as they are rendered on devices and make them available as design components within our UI Kit. What may seem a bit cumbersome at first will ensure that the UI Kit never _overtakes_ code repository. A component that can't be easily built using our technology should not be part of our UI Kit. This way, prototypes we design will always be close to the real thing and all testing we perform will be valid. The diagram below \(fig. 1\) illustrates where and how the UI Kit fits into our design system steam:

![Fig. 1: Steady Flow of Truth: Our design system stream](../../.gitbook/assets/fig_steady_flow.svg)

Next, we quickly go through the stations relevant to the UI Kit. For a complete description, see [Steady Flow of Truth](../infrastructure/steady-flow-of-truth.md).

### UI Kit

Very often, a UI Kit maintained in a modern design tool such as Figma, Adobe XD, or Sketch represents the first step for teams and organizations towards building a design system. The consolidation of components in one central place makes it much easier to knock out consistent prototypes and represents a safe haven to return to from our visual explorations.

### UX Vignettes

### Tweaks



Atomic Design.

Our UI Kit lives in a modern UI design tool such as Figma, Adobe XD or Sketch. While some of these tools provide ways to generate code automatically, the corresponding workflows can make us too dependent on a specific tool or framework. Also, the code quality may not be up to scratch, as there are semantic gaps that still prove hard to bridge from this side of the handoff process. Instead, Lean Design System promotes the adoption of Design Tokens as a much more effective and fluent approach to the integration of design and development efforts. For that reason \(and as we can see in fig. 1\), the UI Kit should always be based on the latest definitions in our code repository. In other words, we quite literally trace components exactly as they are rendered on devices and make them available as design components within our UI Kit. What may seem a bit cumbersome at first will ensure that the UI Kit never takes the lead over the code repository. A component that can't be easily built using our technology should not be part of our UI Kit. This way, prototypes we design will always be close to the real thing and all testing we perform will be valid. We should always only have one central and shared UI Kit file \(or file structure in the case of a very large or complex component library\).



## Where this tactic fits in

{% tabs %}
{% tab title="🙏  This tactic benefits from" %}
Diligently refactoring our design system artifacts will prevent our repositories from cluttering.

{% page-ref page="../actions/clean-up.md" %}
{% endtab %}

{% tab title="💪  This tactic supports" %}
Building a UI Kit will train our systems thinking capabilities.

{% page-ref page="../actions/think-systems.md" %}
{% endtab %}
{% endtabs %}

#### Authors and contributors

D. Kurfess


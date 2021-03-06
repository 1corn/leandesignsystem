---
description: >-
  By constantly optimizing and simplifying our designs and implementations, we
  prune away redundancies and imperfections.
---

# Tidy up!

Lean Design System encourages an approach of letting structures, workflows, and components evolve through project work and design explorations instead of having a long upfront \(Waterfall-like\) planning phase. If left entirely unchecked, such a natural flow may lead to clutter, unwanted variance, and other deficiencies we better avoid if we are to develop an effective and efficient design system.

{% hint style="info" %}
Ideas around the emergent design system are probably best summarized in [Minimum Viable Design System](../principles/minimum-viable-design-system.md) and [Steady Flow of Truth](../infrastructure/steady-flow-of-truth.md).
{% endhint %}

## Commit to consistent improvement

In software development, the term _refactoring_ describes the improvement of existing code without changing its \(external\) behavior. This can refer to better aligning code with agreed-upon conventions, eliminating redundancies, or the act of simplification. When cultivating a dynamic design system \(and especially when following Lean Design System methodology\) everyone involved should make a habit of refactoring any deficient artifact they come in contact with. What this means is, after completing a task, we should always try to clean up a couple issues we noticed—a good rule-of-thumb is aiming to fix slightly more issues than we caused. When we add a new component to a library \(whether in our [`UI Kit`](../artifacts/ui-kits.md), in our [`Design Tokens`](../artifacts/design-tokens.md) repository, or our [`written documentation`](../artifacts/a-living-handbook.md)\) we make it a part of our routine to repair the world around it. Even just a little regular pruning can prevent our system from cluttering up. As long as we all commit to it and stay diligent, our system will steadily evolve towards its optimal design—one refactoring at a time. Collective ownership of design system components, as outlined in [`Win Friends, Not Battles`](../principles/win-friends-not-battles.md) and enabled by [`Design Codification`](../principles/design-codification.md), helps us to adopt this habit, as it allows us to work on any component without having to wait for somebody else. If we notice an imperfection, we can eradicate it right away. Improving a design system component can mean many things, including:

* More clearly defining its role and dependencies within the system
* Simplifying its design and definitions without sacrificing functionality
* Improving its consistency \(i.e., eliminating unwanted variance\)
* Improving its usability and visual design
* Eliminating any redundancies \(in the code, but also in our [`UI Kit`](../artifacts/ui-kits.md)\)
* Improving written documentation \(see: [`A Living Handbook`](../artifacts/a-living-handbook.md)\)
* Eliminating discrepancies between repositories \(see: [`Steady Flow of Truth`](../infrastructure/steady-flow-of-truth.md)\)

## Beach cleaning!

Besides regular clean-ups, we should also consider setting aside a few hours a week to implement a planned beach cleaning session. During such a beach cleaning,  we only refactor and optimize existing components. We can either agree on specific areas per session or choose individually. This might be a tough sacrifice \(time-wise\), especially for smaller teams— but it will almost certainly be worth it in the long run. We should view it as a steady deposit, allowing us to constantly pay down design and technical debt, which would otherwise accumulate and clog up our machine.

## Where this tactic fits in

{% tabs %}
{% tab title="🙏  This tactic benefits from" %}
Adopting collective ownership as outlined in Win Friends, not Battles will help us properly and quickly refactor the individual components of our design system.

{% page-ref page="../principles/win-friends-not-battles.md" %}
{% endtab %}

{% tab title="💪  This tactic supports" %}
Regular clean-ups will help us keep the interfaces between our design system building blocks clean and flexible.

{% page-ref page="../infrastructure/radical-modularity.md" %}

Diligently refactoring our design system artifacts will prevent our repositories from cluttering up.

{% page-ref page="../artifacts/design-tokens.md" %}

{% page-ref page="../artifacts/a-living-handbook.md" %}

{% page-ref page="../artifacts/ui-kits.md" %}
{% endtab %}
{% endtabs %}

#### Authors and contributors

D. Kurfess


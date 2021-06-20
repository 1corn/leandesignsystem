---
description: We always build and design with systems in mind.
---

# Think Systems!

> Designing and building with systems in mind helps us arrive at more purposeful \(i.e., less arbitrary\) solutions.

Think Systems! fosters scalable and sustainable product development in a decentralized way, as it encourages all of us to adopt a systems mindset on an individual level. Even before we commit to building a design system, we can \(and should\) start to build with systems in mind. This entails constantly being on the lookout for any variances, redundancies, and bottlenecks in our daily work and processes, so we can explore ways to eliminate them. For instance, when we engineer or design new features, we should consider how each element might later be described as a reusable component and fit into a larger system, even if such a system does not currently exist. In our technical implementations, we think about what kind of abstraction layers might come in handy in the future, enabling us to more easily introduce changes such as an update to our design language or an additional theme more seamlessly. By over-engineering certain elements—like building a modular SCSS architecture even for a simple website or an extensive [UI Kit](../artifacts/ui-kits.md) for a one-off customer project—we refine our design systems thinking capabilities, preparing us for the task of structuring an actual component and pattern library later on. We train ourselves to anticipate architectural challenges and needs before they arise. Moreover, these additional efforts might improve our daily work right away or produce structures we'll be able to re-use in other contexts or projects. Still, even in a worst-case scenario, we most certainly learned something in the process: We developed a better understanding of gaps in our considerations and a heightened sensibility for the intricacies \(and dependencies\) of our designs and implementations. 

When we design a new UI component or review and update an existing one, we remind ourselves to consider every dimension relevant to its integration into a larger system, including:

* Its intent and use cases
* Its form and implementation
* Its place within the system \(think hierarchy, nesting, dependencies\)
* Its variants and configurations
* How theming will affect it
* Its alternatives, i.e. similar elements \(in order to avoid redundancy\)
* Its UX validation parameters \(how will we test it?\)
* Its accessibility aspects

Designing and building with systems in mind helps us arrive at more purposeful \(i.e., less arbitrary\) solutions. A good training exercise for developing such a mindset is conceiving an efficient and versatile [Design Tokens](../artifacts/design-tokens.md) repository.

## Where this tactic fits in

{% tabs %}
{% tab title="🙏  This tactic benefits from" %}
Conceiving a Design Tokens structure or building a UI Kit alongside a project can help us refine our systems thinking capabilities.

{% page-ref page="../artifacts/design-tokens.md" %}

{% page-ref page="../artifacts/ui-kits.md" %}
{% endtab %}

{% tab title="💪  This tactic supports" %}
Think Systems! outlines a mindset we can adopt on an individual level that helps us start shaping our design system's first minimum viable building blocks.

{% page-ref page="../principles/minimum-viable-design-system.md" %}

Think Systems! provides guidance and purpose for our refactoring efforts.

{% page-ref page="clean-up.md" %}
{% endtab %}
{% endtabs %}

#### Authors and contributors

D. Kurfess


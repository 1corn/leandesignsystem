---
description: >-
  We start with the building blocks we need today and validate them in the the
  context of ongoing projects at the first opportunity.
---

# Minimum Viable Design System

The planning and implementation of a modern design system can quickly turn into a formidable undertaking, requiring significant investments \(regarding time, capital and people\). Oftentimes, the obstacles associated with it prove insurmountable for resource-constrained organizations. Furthermore, an overly monolithic approach, where months and even years are spent building extensive libraries, poses the risk of producing unfit solutions in the end. We can't predict the future and working towards uncertain outcomes may have costly consequences.

Minimum Viable Design System attempts to address these concerns and is centered around the following 3 core ideas—which also underpin the Lean Design System methodology as a whole:

* **Start today:** The best time to start cultivating a design system was the day we started working together. The second best time is now.
* **Solve today's problems:** The success of a design system isn't defined by its comprehensiveness or depth of implementation, but solely by the extent to which it helps us solve real problems and generate compelling products.
* **Validate continuously:** Building the components needed today and starting to use them immediately in prototypes and real projects will help us evaluate their fitness and make swift adjustments.

Let's have a closer look at each of the 3 ideas to learn how they make the concept of design systems more accessible and what it means to apply them in practice.

## Start today

When we're already building digital products in a team, there really isn't any reason to delay the systemization of design work. Modern digital tools and organizational paradigms allow for tremendous scalability—when applied properly. There are many simple steps we can take today in order to start establishing our own design system, no risks involved. Lean Design System promotes the steady cultivation of design system structures along real problems, projects and experiences—and Minimum Viable Design System provides us with a helpful reference frame around the entire methodology. Other tactics such as [`A Name and a Place`](../infrastructure/a-name-and-a-place.md), [`Design Tokens`,](../artifacts/design-tokens.md) and [`Think Systems!`](../actions/think-systems.md) can all serve as starting points to develop first routines and artifacts.

## Solve today's problems

In order to understand and apply Minimum Viable Design System, we first need to consider the definition of design systems themselves: At what point does a collection of front-end components, UI kits, and guidelines become a design system? Lean Design System promotes a very pragmatic and straightforward interpretation: Any socio-technical system that makes our product development successes repeatable and transferable is a design system. Such a success can be design-related, but also of technical or organizational nature. What elements and processes it actually encompasses entirely depends on our specific problems, challenges and goals. This liberating notion allows us to focus all our efforts on components that are key to our unique value proposition. If, for example, data analytics is the core of our business, our design system may only contain data visualization patterns in the beginning. If we're digitizing maintenance workflows, we may start by developing innovative navigation paradigms and documenting them as re-usable patterns. If we're a fast-moving software startup, our design system might just be an automated pipeline for now that allows designers to rapidly evaluate changes in a realistic test environment. And so on.

> Any socio-technical system that makes our product development successes repeatable and transferable is a design system.

After we agreed on our priorities, we can confidently draw on freely available resources in other areas. A design system that grows organically will have gaps in the beginning, that's inevitable. But there's no shame in utilizing existing libraries, frameworks and assets to fill them—at least for the time being. We can always replace them with home-cooked implementations at a later point, should the need \(or desire\) arise. [`Radical Modularity`](../infrastructure/radical-modularity.md) outlines a sustainable approach to utilizing external resources.

Examples of 3rd party resources we can fall back on include:

* Full-blown **front-end frameworks** like [Bootstrap](https://getbootstrap.com/) and [Material-UI](https://material-ui.com/) can be used to kickstart a front-end component library. The tactic [`Radical Modularity`](../infrastructure/radical-modularity.md) describes how we can use their native theming capabilities and [`Design Tokens`](../artifacts/design-tokens.md) to align their look-and-feel with our own brand identity.
* Versatile **illustration libraries** and frameworks such as [blush.design](https://blush.design/) allow us to create descriptive visuals for app tutorials or marketing websites. Our experience with them can also teach us how to create our own library later on.
* A unique **icon library** can be an important building block of a distinctive brand design language. However, there are hosts of resources available online \(which are either free and open source or at least more affordable than producing them in-house\) and among them, we should almost certainly be able to find a few options suitable for our needs.

The structure of a design system can be sliced many different ways. Understanding the individual parameters making it up is key to identifying potentials and gaps. The following diagram illustrates a typical design system anatomy and can serve as a map and canvas to locate our top priorities: 

![Fig. 1: A typical anatomy of a design system](../../.gitbook/assets/fig_anatomy.svg)

A \(very lightweight\) knowledge hub—like a wiki, GitBook or even just a cloud spreadsheet—can function as a reference point for all our efforts. Here we document all the repositories we're establishing, as well as our external resources we currently use. Fig. 2 \(below\) proposes a structure with categories and subcategories to organize the individual building blocks. The process of setting up and updating such a documentation can be underpinned with semi-regular cross-functional workshops. These should be conducted in an uncomplicated, straightforward manner and can be initiated with a few introductory questions aimed at steering the discussion towards people, interactions, and specific struggles:

* Which new activities or processes recently emerged around design/development handoffs?
* Can we think of tasks and steps that seem overly repetitive and cumbersome?
* How can I personally simplify and support the work of my teammates?
* Can I think of ways in which my team can help me streamline my work and remove obstacles?

![Fig. 2: Typical element structure of a design system](../../.gitbook/assets/fig_elements.svg)

## Validate continuously

> Lean Design System methodology values exploration over planning. We try to aim in the right direction and correct our course as needed.

To summarize the ideas outlined above: We treat all aspects of our design work and the design/development handoff as parts of a living design system. We clarify each element's role and function in this system and maintain a lightweight documentation alongside our efforts. We draw on external resources to fill any gaps—with the goal of making each component we create usable from the get-go, even if not yet embedded in a fully-fledged library.

![Fig. 3: The Minimum Viable Design System approach](../../.gitbook/assets/fig_mvds.svg)

Lean Design System methodology values exploration over planning. Instead of waiting for a perfect, all-encompassing solution, we try to aim in the right direction, use \(and validate\) components as soon as possible and correct course as needed. If a process or a component doesn't stand the test of real-world application, we go back and optimize it or explore a different approach altogether. The building blocks of a design system are digital in nature and thus, we can freely re-combine, adapt and optimize them. With the right infrastructure in place, we can even propagate changes throughout our product portfolios after initial delivery. If we went down a wrong path, we can always backtrack again, if we made a bad decision, we can reconsider it; we don't have to be overly cautious—instead, we should experiment freely and constantly produce usable results which we can validate in practice.

## Where this tactic fits in

{% tabs %}
{% tab title="🙏  This tactic benefits from" %}
Keeping the interfaces between our own implementations and 3rd party resources clean will help us stay flexible and mitigate risks and dependencies.

{% page-ref page="../infrastructure/radical-modularity.md" %}

Think Systems! outlines a mindset we can adopt on an individual level that helps us start shaping our design system's first minimum viable building blocks.

{% page-ref page="../actions/think-systems.md" %}

UX Vignettes make for great _minimum viable conversations._ We can use them to validate our assumptions quickly and avoid spending too much time on dead-end paths.

{% page-ref page="../artifacts/ui-kits.md" %}
{% endtab %}

{% tab title="💪  This tactic supports" %}
MVDS provides a helpful frame of reference for establishing our system repositories and thus supports Steady Flow of Truth, A Name and a Place, and A Living Handbook.

{% page-ref page="../infrastructure/steady-flow-of-truth.md" %}

{% page-ref page="../infrastructure/a-name-and-a-place.md" %}

{% page-ref page="../artifacts/a-living-handbook.md" %}
{% endtab %}
{% endtabs %}

#### Authors and contributors

[D. Kurfess](https://twitter.com/1corn)


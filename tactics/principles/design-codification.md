---
description: >-
  Design Codification is the belief that all aspects shaping digital products
  should be defined as code, versioned, and collectively owned.
---

# Design Codification

In software design there's a saying that _"if it isn’t documented, it doesn’t exist"_. Design Codification is driven by the idea that _"if it isn't codified, it won't persist"_. It's a guiding principle based on the belief that digital product development should be underpinned by semantic software code that can be written, reviewed, adapted, and owned by developers, just as well as by \(visual **and** UX\) designers.

An effective design system makes our design and development successes repeatable and transferable. The systematic codification of design represents a lean approach to avoiding repetitive work and unwanted deviations from guidelines, as it minimizes \(or even eliminates\) the need for strict governance processes. Through collective code ownership \(as outlined in [Win Friends, not Battles](win-friends-not-battles.md)\) and continuous optimization \(as outlined in [Steady Flow of Truth](../infrastructure/steady-flow-of-truth.md) and [Tidy up!](../actions/clean-up.md)\) a codified component repository matures with each project and interaction. Digital products are composed of software code and by embracing code as a building material we unlock several powerful concepts and mechanisms related to computational processing, including:

* Software code **can be stored and versioned** in repositories. We can perform comparisons and mergers of different iterations. We can create forks and branches to experiment with and expand our libraries.
* Repositories and versioning allow for **collective code ownership**, as we can easily trace, evaluate and revert changes.
* Working on shared repositories also allows for sandbox environments and **automated CI/CD pipelines** to be established that enable developers and designers to validate changes right away without having to wait for deployments.
* The same concept makes it possible to **propagate changes** into already deployed products.
* Codification allows for **code-based manipulations** of design artifacts at runtime, like coloring or animating icons using SVG and JavaScript, eliminating error-prone handoffs and tedious export processes.
* Unlike written guidelines, software code is **unambiguous**, helping us to prevent unwanted variance.
* Definitions stored as code provide us with powerful levers to make big changes with little effort through **nesting and batch processing**.
* A code-based style repository can even allow us to generate an **automated documentation**. It's almost trivial to build a simple web page previewing our component library which directly imports definitions from our Design Tokens repository.

Design Codification, if done right, enables seamless communication and collaboration between design and development. It establishes a shared language that can be adopted by everyone working on digital products. Developers can learn about design-related nuances and dependencies, while designers gain a better understanding of the technical realities underpinning the technology they're working with.

Ultimately, the process of Design Codification can result in a fully codified design system with automated pipelines, automated documentation, and a fully interweaved collaboration between design and development. But there are many incremental steps we can take towards this goal and even explore hybrid approaches in which we only codify certain aspects of our design work. Listed below are three low-barrier examples for Design Codification:

* [Design Tokens](../artifacts/design-tokens.md) are a great way to get started with Design Codification. [Design Tokens](../artifacts/design-tokens.md) are codified design attributes that can be defined, understood and applied by developers and designers alike.
* Information architecture can be documented as a data model straight away. With the support of engineering, an information architect can maintain information in such a way that they can be used directly for other purposes, like structuring databases or generating sitemaps.
* Icons and vector illustrations can be stored as SVGs, enabling script-based manipulations like color changes, animations and lossless scaling.

To catalyze the process of Design Codification, it can be helpful to establish the role of a dedicated front-of-the-front-end developer within the team \(which might be filled by a former code-savvy designer, a former design-savvy developer, or an entirely new resource\) working specifically on the interfaces between design and development. According to Brad Frost's [definition](https://bradfrost.com/blog/post/front-of-the-front-end-and-back-of-the-front-end-web-development/), a front-of-the-front-end developer is _"a web developer who specializes in writing HTML, CSS, and presentational JavaScript code"_. A good understanding of \(visual and UX\) design and state-of-the-art UI implementation paradigms will help to fully grasp the respective goals and challenges.

## Where this tactic fits in

{% tabs %}
{% tab title="🙏  This tactic benefits from" %}
{% page-ref page="../artifacts/design-tokens.md" %}
{% endtab %}

{% tab title="💪  This tactic supports" %}
{% page-ref page="win-friends-not-battles.md" %}

{% page-ref page="../infrastructure/steady-flow-of-truth.md" %}
{% endtab %}
{% endtabs %}

#### Authors and contributors

D. Kurfess


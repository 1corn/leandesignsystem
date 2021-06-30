---
description: We articulate and document a shared design system mission.
---

# A Living Handbook

Lean Design System methodology prioritizes experimentation over documentation and advocates a lightweight approach to written guidelines, at least during the early stages of building a design system. A lot of information can be stored and maintained as comments within our [UI Kit](ui-kits.md) or [Design Tokens](design-tokens.md) code; however, we will probably still need some form of knowledge hub alongside our component repositories, where we outline the structure and scope of our design system and write down the principles, norms, and workflows that guide our work. Such supporting documentation should be simple, brief, and precise and stored in a collaborative format, like a markdown repository, a cloud spreadsheet, or a wiki. It should include the following elements:

* **Scope:** We reference all elements that we consider to be part of our design system and specify where they're maintained, as well as the workflows around them.
* **Integrations**: We reference all 3rd party frameworks and resources we're utilizing, explain how they're integrated and what we need to keep in mind in order to use them as intended.
* **Technical setup:** If applicable, we explain development environments and technical setups like Gulp automations or how to trigger build pipelines. Here we may also specify our currently preferred design tooling and code guidelines.
* **Mission:** We articulate a design system mission statement outlining the, goals, norms, and values that guide our work, making our implicit practices explicit. Our mission statement should be revisited \(and, if need be, updated\) regularly.

Through the process of articulating thoughts we can clarify ideas, avoid misunderstandings and explain abstract concepts—especially if done collaboratively and cross-functionally. We don’t have to make a document perfect before sharing it—we make it good enough to convey our ideas and then improve it in a collaborative fashion.

The Lean Design System documentation is freely available under a Creative Commons license and can serve as a foundation for a lightweight design system documentation. It is written in markdown language and stored in a [Git repository](https://github.com/1corn/leandesignsystem/tree/main), which makes it easy to fork, customize and extend. Individual parts can be adopted without change, edited as needed, or deleted altogether. The diagram below \(fig. 1\) illustrates the structure of the documentation: 

A codified documentation as outlined here, where information is stored in a repository alongside other codified design components, is a good starting point for a fully automated documentation with live component previews down the road. It also teaches us the use of version control in a very simple, accessible way, as changes can be reviewed using a very low-barrier UI like [GitBook](https://www.gitbook.com/) is offering, GUI-based version control software such as [SourceTree](https://www.sourcetreeapp.com/), or directly via terminal.

## The Holy Grail of design system documentation

The auto-generated documentation that emerges naturally from its underlying design language—with the design system as a translator in the middle—is deemed the holy grail of design documentation by many. However, thanks to the convergence of concepts and technologies in the area of design systems \(such as [Design Tokens](design-tokens.md) and component-based front-end libraries\), this ambitious proposition might soon become an achievable reality, even for smaller teams and organizations. Whatever approach we take, our goal should be to arrive at a documentation directly derived from code, requiring minimal maintenance efforts. Every step we take towards this goal will most definitely improve our design system workflows and communication.

## Where this tactic fits in

{% tabs %}
{% tab title="🙏  This tactic benefits from" %}
Minimum Viable Design System provides a helpful frame of reference for establishing A Living Handbook.

{% page-ref page="../principles/minimum-viable-design-system.md" %}

Design Codification may enable us to build a fully generative documentation.

{% page-ref page="../principles/design-codification.md" %}

Diligently refactoring our design system artifacts, such as written documentation, will prevent our repositories from cluttering up.

{% page-ref page="../actions/clean-up.md" %}
{% endtab %}

{% tab title="💪  This tactic supports" %}
A Living Handbook can serve as a starting point for establishing our design system.

{% page-ref page="../infrastructure/a-name-and-a-place.md" %}

A Living Handbook outlines ways to make our design system more tangible early on and directly supports us in our canvassing efforts.

{% page-ref page="../actions/canvas.md" %}
{% endtab %}
{% endtabs %}

#### Authors and contributors

D. Kurfess


---
description: WORK IN PROGRESS
---

# Design Tokens

[Design Codification](../principles/design-codification.md) represents one of the key principles of Lean Design System, as it enables cross-functional teams to work collaboratively and adopt collective ownership of a design system. However, planning and implementing a comprehensive component library can prove a substantial challenge, even for experienced teams. Taking incremental steps towards this goal will help us get started, especially if we're just getting used to concepts such as design-as-code and radical cross-functionality \(as proposed in [Win Friends, not Battles](../principles/win-friends-not-battles.md)\). Maintaining design aspects in the form of Design Tokens makes for one such approach. According to design system advocate [Jina Anne](https://twitter.com/jina) \(who is also co-chairing the W3C's [Design Tokens Community Group](https://www.w3.org/groups/cg/design-tokens)\):

{% embed url="https://twitter.com/jina/status/1062808011301965825" caption="Jina Anne on Design Tokens" %}

A well thought-out Design Tokens structure constitutes the bedrock of a lean code repository. It provides the DNA for our components and a shared language between domains. A design system based on Design Tokens forces designers and developers to continually form consensus, which promotes a healthy interweaving of skills and responsibilities. Designers are encouraged to form at least a basic understanding of the code in order to define and approve tokens. Front-end developers learn about the intent behind design rules and the relationships between properties by applying design tokens to UI implementations.

Design tokens provide designers and developers with powerful levers to make changes quickly and effectively throughout all layers of the design system and our front-end implementations. These layers include the brand design properties at the core of the design system, higher level themes and custom adaptations, as well as the specific UI component mappings on the surface of a digital product. The following examples will illustrate what structure we need in order to make full use of the concept.

The currently preferred approach to maintaining Design Tokens is storing them in a JSON file, as it's the most widely supported format. From there, all information can be pulled via JavaScript or compiled to CSS. The examples below are written in CSS to make them easier to read for designers who are not yet familiar with JSON.

{% tabs %}
{% tab title="Example 1: Colors" %}
{% code title="design-tokens.scss" %}
```css
// Sub-atomic definitions

.cornflower: #0000ff;
```
{% endcode %}
{% endtab %}
{% endtabs %}

![Fig. 1: Border radius defined on increasingly specific levels](../../.gitbook/assets/anim_tokens_lever.png)

## Where this tactic fits in

{% tabs %}
{% tab title="🙏  This tactic benefits from" %}

{% endtab %}

{% tab title="💪  This tactic supports" %}

{% endtab %}
{% endtabs %}

#### Authors and contributors

D. Kurfess


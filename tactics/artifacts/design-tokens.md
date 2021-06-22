---
description: WORK IN PROGRESS
---

# Design Tokens

[Design Codification](../principles/design-codification.md) represents one of the key principles of Lean Design System, as it enables cross-functional teams to work collaboratively and adopt collective ownership of a design system. However, planning and implementing a comprehensive component library can prove a substantial challenge, even for experienced teams. Taking incremental steps towards this goal will help us get started, especially if we're new to concepts such as design-as-code and radical cross-functionality \(as proposed in [Win Friends, not Battles](../principles/win-friends-not-battles.md)\). Maintaining design aspects in the form of Design Tokens makes for one such approach. According to design system advocate [Jina Anne](https://twitter.com/jina) \(who is also co-chairing the W3C's [Design Tokens Community Group](https://www.w3.org/groups/cg/design-tokens)\):

{% embed url="https://twitter.com/jina/status/1062808011301965825" caption="Jina Anne on Design Tokens" %}

Design Tokens can be described as an abstraction of all aspects shaping the design of digital products. In contrast to hard-coded values maintained all over the place, tokens are the central roots of a scalable and consistent design system.

A well thought-out Design Tokens structure constitutes the bedrock of a lean code repository. It provides the DNA for our components and a shared language between domains. A design system based on Design Tokens forces designers and developers to continually form consensus, which promotes a healthy interweaving of skills and responsibilities. Designers are encouraged to form at least a basic understanding of the code in order to define and approve tokens. Front-end developers learn about the purpose behind design-related decisions and the relationship between properties, as Design Tokens manage to bridge the semantic gap between the designers' intentions and the technical implementation. They provide additional richness to design definitions and make technical and stylistic nuances more tangible to both audiences.

Design tokens also provide designers and developers with powerful levers to make changes quickly and effectively throughout all layers of the design system and our front-end implementations. These layers include the brand design properties at the core of the design system, higher level themes and custom adaptations, as well as the specific UI component mappings on the surface of a digital product. The following examples will illustrate how we can structure a Design Tokens repository so we can make full use of the concept.

{% hint style="info" %}
The currently preferred approach to maintaining Design Tokens is storing them in a JSON file, as it's the most widely supported format. From there, all information can be pulled via JavaScript or compiled to CSS. The examples below are written in SCSS to make them easier to read for designers who are not yet familiar with JSON.
{% endhint %}

First, we take a look at colors. More specifically, we will learn how a color definition is passed through the semantic layers of a Design Tokens structure all the way from the most abstract level of the color palette to the tangible level of a UI mapping. Subsequently, we apply the same idea to border radii. Similarly, we start with an abstract, subatomic definition and specify increasingly semantic mappings. Now let's see what the corresponding SCSS would look like—switch between the two tabs to check out both examples:

{% tabs %}
{% tab title="Example 1: Colors" %}
```css
/****
* Subatomic definitions: Our color palette 
****/

$cornflower: #5784FF; 
/* We assign a value to a new color in our color palette */


/****
* Getting more specific: Our color scheme 
****/

$primary-color: $cornflower;
/* On the next level, we assign the value cornflower to our primary color */


/****
* UI mapping: Mapping sub-atomic defintions to UI components 
****/

$color-btn-cta: $primary-color;
/* In the last step, our primary color is assigend to the cta button */
```
{% endtab %}

{% tab title="Example 2: Border Radii" %}
```css
/****
* Subatomic definitions: Our color palette 
****/

$cornflower: #5784FF; 
/* We assign a value to a new color in our color palette */


/****
* Getting more specific: Our color scheme 
****/

$primary-color: $cornflower;
/* On the next level, we assign the value cornflower to our primary color */


/****
* UI mapping: Mapping sub-atomic defintions to UI components 
****/

$color-btn-cta: $primary-color;
/* In the last step, our primary color is assigend to the cta button */
```
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


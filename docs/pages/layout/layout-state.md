---
title: Layout States
permalink: /layout/layout-state

flex_states:
    - title: Default
      url: /layout/states/default
    - title: Is Reddit Admin
      url: /layout/states/distinguished-admin
    - title: Is Reddit Moderator
      url: /layout/states/distinguished-mod
    - title: Has Awards
      url: /layout/states/has-awards
    - title: NSFW
      url: /layout/states/is-nsfw
    - title: Spoiler
      url: /layout/states/is-spoiler
    - title: Has Link Flair
      url: /layout/states/has-link-flair
    - title: Has Thumbnail
      url: /layout/states/has-thumbnail
    - title: Has Thumbnail Image
      url: /layout/states/has-thumbnail-image
    - title: Has Media
      url: /layout/states/has-media
    - title: Upvoted by User
      url: /layout/states/is-upvote
    - title: Downvoted by User
      url: /layout/states/is-downvote
---

Layout States are used to apply Modifiers when certain conditions defined by the State pass. They are the `if-else` conditionals in Flex. 

States can be used to show or hide spoiler tags, change the style of the author if they are a Reddit moderator, change the color of the score if the user upvoted the post, etc.

{% assign src="layout_states.png" | prepend: "/assets/images/" | relative_url %}
[![Flex States]({{src}}){:.w-66}]({{src}})
{:.text-center}

## Default & Condition States

The first, top-most state of a Component is the Default State. Default States are always active, meaning their Modifiers are always applied. Use this state to set up the baseline of how the content should usually look.

The remaining states are Condition States. Condition States are dormant and do not apply any Modifiers. When the conditions defined by the State pass, they become active and apply their Modifiers _on top of_ of the Default State, taking precendence and overriding any Modifiers also declared in the Default State.

Condition States are evaluated from top to bottom. Evaluation stops when the first Condition State passes.

## List of Condition States

{%- for item in page.flex_states %}
- [{{item.title}}]({{item.url | relative_url}})
{%- endfor %}

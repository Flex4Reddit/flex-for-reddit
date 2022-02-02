---
title: Flex for Reddit
permalink: /
excerpt: "A unofficial, highly customizable Android app for Reddit."
toc: false
classes: wide
---
Flex for Reddit is an unofficial, highly customizable Android app for Reddit.

## Customizable Themes

Flex allows the complete customization of themes. From primary colors to text colors to upvote/downvote colors to Reddit moderator/admin colors. Everything is customizable.

{% assign items = site.data.index.themes %}
{% for item in items -%}
{% assign src = item.path | prepend: "/assets/images/" | relative_url %}
[![{{item.alt}}]({{src}}){:.gallery-{{items.size}}}]({{src}})
{%- endfor %}
{:.text-center}

## Customizable Layouts

What makes Flex stand out is the ability to customize post layout. A left-handed user may prefer to have images moved to the left side of the screen. A user with poor vision may prefer larger images.  
These layouts can all be achieved with Flex.

{% assign items = site.data.index.layouts %}
{% for item in items -%}
{% assign src = item.path | prepend: "/assets/images/" | relative_url %}
[![{{item.alt}}]({{src}}){:.gallery-{{items.size}}}]({{src}})
{%- endfor %}
{:.text-center}

## Flex Customization Editor

Flex provides a powerful editor that allows users to modify Android View properties directly. Be warned, the Android View system is complex, and long-term exposure to the Andorid View system may slowly turn you into a developer. The Guides & Tutorials here will help you navigate this perilous journey.

{% assign src="layout_editor.png" | prepend: "/assets/images/" | relative_url %}
[![Layout Editor]({{src}}){:.gallery}]({{src}})
{:.text-center}

Once you get the hang of it, you can create some pretty nitfy experiences. To get an idea, head over to [r/matrix](https://old.reddit.com/r/matrix) in the app and check out the hacker-green theme based on its subreddit style.

{% assign items = site.data.index.matrix %}
{% for item in items -%}
{% assign src = item.path | prepend: "/assets/images/" | relative_url %}
[![{{item.alt}}]({{src}}){:.gallery-{{items.size}}}]({{src}})
{%- endfor %}
{:.text-center}

## Give Flex for Reddit a whirl!

Interested to give it a go? Flex for Reddit is available on Google Play.

<a href='https://play.google.com/store/apps/details?id=ai.brownian.flex4reddit'><img width="66%" alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png'/></a>
{: .text-center}

## Theme & Layout Guides

Learn more about Flex's theme & layout editing system.

[Theme Customization Guide]({{ "/theme/theme-system" | relative_url }}){: .btn .btn--info}

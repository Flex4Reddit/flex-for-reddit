---
title: Flex for Reddit
nav_order: 1
description: "A unofficial, highly customizable Android app for Reddit."
permalink: /
---

# Flex for Reddit
{: .fs-9 }

A unofficial, highly customizable Android app for Reddit.
{: .fs-6 .fw-300 }

<!-- [Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on GitHub](https://github.com/pmarsceill/just-the-docs){: .btn .fs-5 .mb-4 .mb-md-0 } -->

---

## Customizable Themes

Flex allows the complete customization of themes. From primary colors to text colors to upvote/downvote colors to Reddit moderator/admin colors. Everything is customizable.

{:style="text-align:center;"}
{% for item in site.data.index.themes -%}
<img src="assets/images/{{ item.path }}" width="24%" height="24%" alt="{{ item.alt }}"/>
{%- endfor %}

## Customizable Layouts

What makes Flex stand out is the ability to customize post layout. A left-handed user may prefer to have images moved to the left side of the screen. A user with poor vision may prefer larger images.  
These layouts can all be achieved with Flex.
 
{:style="text-align:center;"}
{% for item in site.data.index.layouts -%}
<img src="assets/images/{{ item.path }}" width="24%" height="24%" alt="{{ theme.alt }}"/>
{%- endfor %}

## But How...?

Flex provides a powerful editor that allows users to modify Android View properties directly. Be warned, the Android View system is complex, and long-term exposure to the Andorid View system may slowly turn you into a developer. The Guides & Tutorials here will help you navigate this perilous journey.

Once you get the hang of it, you can create some pretty nitfy experiences. To get an idea, head over to [r/matrix](https://old.reddit.com/r/matrix) in the app and check out the hacker-green theme based on its subreddit style.

{:style="text-align:center;"}
{% for item in site.data.index.matrix -%}
<img src="assets/images/{{ item.path }}" width="24%" height="24%" alt="{{ theme.alt }}"/>
{%- endfor %}

## Give Flex for Reddit a whirl!

Interested to give it a go? Flex for Reddit is available on Google Play.

{:style="text-align:center;"}
<a href='https://play.google.com/store/apps/details?id=ai.brownian.flex4reddit'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png' width="50%"/></a>

## Theme & Layout Guides

Learn more about Flex's theme & layout editing system.

[Theme Editor Guide]({% link pages/theme_editor.md %}){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
[Layout Editor Guide]({%link pages/layout_editor.md %}){: .btn .fs-5 .mb-4 .mb-md-0 }

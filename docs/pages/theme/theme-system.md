---
title: Flex Theme System
permalink: /theme/theme-system
---

Flex's theme system allows users to customize colors in the app. Flex also allows customization of Reddit-specific colors such as upvote/downvote colors and moderator/admin colors.

Flex's theme system borrows heavily from [Material Design's Color System][1]. 

## Primary & Secondary Colors

Primary color is the color displayed most frequently in the app. Secondary color is the accent color.

You can read more about Primary and Secondary Colors on [Material Design][1].

## _On_ Colors

_On_ colors (_On-Primary_, _On-Secondary_, etc.) are typically used when content, such as text & icons, are overlaid on top of another color.

For example, the action bar uses the _Primary_ color for its background. Since the hamburger menu and title is overlaid on top of the background, they are controlled by the _On-Primary_ color.

You can read more about On Colors on [Material Design][1].

{% assign src="theme_color_names.png" | prepend: "/assets/images/" | relative_url %}
[![On Colors]({{src}}){:.w-auto}]({{src}})
{:.text-center}

## Text Emphasis

Text colors can further be categorized into high, medium & low emphasis colors. Flex uses the _On-Background - Medium Emphasis_ specifically for description text and subtitles.

You can read more about Text Colors on [Material Design][2].

## Reddit Colors

Reddit colors are used to colorize content that is specific to Reddit, such as upvote/downvote colors, moderator/admin colors, NSFW/Spoiler colors, etc.

Go to the [Theme Editor]({{ "/theme/change-colors" | relative_url }}) in the app to see what type of content is supported.


[1]: https://material.io/design/color/the-color-system.html#color-theme-creation 
[2]: https://material.io/design/color/text-legibility.html#text-backgrounds

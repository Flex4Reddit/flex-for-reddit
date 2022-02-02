---
title: Create a New Theme
permalink: /theme/create-theme
---

Go to the theme overview page, which displays all available themes stored on the device.

1. Open the **Navigation Drawer**.
2. Click on **Settings**.
3. Click on **My Themes**.

Themes can be categorized into **Flex Themes** and **User Themes**.

## Flex Themes

Flex Themes are themes built into Flex by default and cannot be modified. They are the starting point of theme customization.

## User Themes

User Themes are modifiable themes created by the user. They are stored locally on the device. If you use Clear Data on the app, all User Themes will be deleted.

{% assign src="theme_overview.png" | prepend: "/assets/images/" | relative_url %}
[![Theme Overview]({{src}}){:.w-50}]({{src}})
{:.text-center}

## Create a New Theme

To create a new theme, 
1. Click on the **More** button on the right of an existing theme. 
2. Then click on **Duplicate**. 
3. This will create a new User Theme. You may need to scroll to the top to see it.
4. Click on the User Theme to begin customizing.

{% assign src="theme_duplicate.png" | prepend: "/assets/images/" | relative_url %}
[![Create New Theme]({{src}}){:.w-50}]({{src}})
{:.text-center}

## Rename Theme & Description

The new theme's name & description can be changed to your liking.
1. Click on the **More ** button on the right.
2. Then click on **Rename**.
3. Click on the property you would like to change.

{% assign items = site.data.theme.rename %}
{% for item in items -%}
{% assign src = item.path | prepend: "/assets/images/" | relative_url %}
[![{{item.alt}}]({{src}}){:.gallery-{{items.size}}}]({{src}})
{%- endfor %}
{:.text-center}


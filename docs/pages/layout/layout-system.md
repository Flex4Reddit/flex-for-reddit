---
title: Flex Layout System
permalink: /layout/layout-system

flex_components:
    - name: Text
      android_name: TextView
      android_url: https://developer.android.com/reference/android/widget/TextView
    - name: Text Span
      android_name: TextView
      android_url: https://developer.android.com/reference/android/widget/TextView
    - name: Image
      android_name: ImageView
      android_url: https://developer.android.com/reference/android/widget/ImageView

flex_containers:
    - name: Linear
      android_name: Linear Layout
      android_url: https://developer.android.com/reference/android/widget/LinearLayout
    - name: Flex
      android_name: Flexbox Layout
      android_url: https://github.com/google/flexbox-layout
    - name: Card
      android_name: Card View
      android_url: https://developer.android.com/reference/androidx/cardview/widget/CardView

reddit_components:
    - name: Award
    - name: Media Preview
    - name: Markdown

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

Flex's layout system allows users to customize the display of content. You can adjust the shape and size of any content, as well as the position of content.

## Components - The Basic Building Block

Components are the basic building block of a Layout. They determine the type of Android View to create and how to decorate the View.

For example, **Text Components** are used for displaying text, and support Modifiers for customizing text; while **Image Components** are used for rendering images, and support Modifiers for customizing images.

Click on a component for more details.

| Component | Android View |
|---|---|
{%- for item in page.flex_components %}
| {{item.name}} Component | [{{item.android_name}}]({{item.android_url}}) |
{%- endfor %}

### Container Components

Container Components are used to oragnize the position of other components.

For example, **Linear Components** position content compnents one after another, like a vertical list. **Flex Components** position content components horizontally and can overflow to the next row when more space is needed.

Click on a component for more details.

| Container Component | Android View |
|---|---|
{%- for item in page.flex_containers %}
| {{item.name}} Component | [{{item.android_name}}]({{item.android_url}}) |
{%- endfor %}

### Reddit Components

Reddit Components are special components used to display complex Reddit data.

For example, the **Award Component** is used to display Reddit awards. The **Media Preview Component** is used to display image/videos if the post contains multimedia.

Click on a component for more details.

| Reddit Component |
|---|
{%- for item in page.reddit_components %}
| {{item.name}} Component |
{%- endfor %}

## Modifiers

Modifiers control the look and behavior of Components. From text size to content padding, you can customize Components by changing its Modifier values. Click on a Component above to see the full list of Modifiers available.

### View Modifiers

View Modifiers are Modifiers supported by all Components. They allow the customization of common attributes such as width, height, padding & margin.

## [States]({{ "/layout/layout-state" | relative_url }})

States are used to apply Modifiers when certain conditions defined by the State pass. They are the `if-else` conditionals of Flex. 

States can be used to show or hide spoiler tags, change the style of the author if they are a Reddit moderator, change the color of the score if the user upvoted the post, etc.

{% assign src="layout_states.png" | prepend: "/assets/images/" | relative_url %}
[![Flex States]({{src}}){:.w-66}]({{src}})
{:.text-center}

Click on a state for more details.

| State |
|---|
{%- for item in page.flex_states %}
| {{item.name}} Component |
{%- endfor %}

---
title: View Modifiers
permalink: /layout/modifiers/view
---

- Width

  Width of the component.

- Height

  Height of the component.

- Visibility

  Show or hide the component.

- Layout Gravity

  Controls the alignment of children components. Can only be used by [Container Components](../layout-system#container-components); has no effect in other components.

- Layout Weight [Android Docs](https://developer.android.com/guide/topics/ui/layout/linear#Weight)

  Tells the parent component to distribute space based on this value relative to sibling components' Layout Weight.

  For example, a Linear Component has 3 Text Components. The 3 Text Components specifies Layouts Weight of 4, 9 & 7. This will cause the 3 Text Components to take up 20% (4/4+9+7), 45% (9/4+9+7) & 35% (7/4+9+7) of total space, respectively.

  Sibling components that do not specify Layout Weight will simply not participate in the space distribution; its height & width will not be overriden.

- Start/End/Top/Bottom Padding

  Space between the components border and its content.



- Start/End/Top/Bottom Margin

  Space around the components border.

{% capture notice-text %}
#### _Start_ & _End_{:.no_toc} vs Left & Right

Start & End are modifiers that support both Left-to-Right (English, Spanish, etc.) and Right-to-Left languages (Arabic, Hebrew, etc.).

Start and End refers to left and right respectively in Left-to-Right languages; and switches to right and left respectively in Right-to-Left languages.
{% endcapture %}
<div class="notice--primary">
  
  {{ notice-text | markdownify }}
</div>

- Background

  Background of the component.

- Click

  Behavior when the component is clicked.

- Long Click

  Behavior when the component is long-clicked.

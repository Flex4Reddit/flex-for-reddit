Go to the {{include.create_type}} overview page, which displays all available {{include.create_type}}s stored on the device.

1. Open the **Navigation Drawer**.
2. Click on **Settings**.
3. Click on **My {{include.create_type | capitalize}}s**.

{% assign src=include.create_type | append: "_overview.png" | prepend: "/assets/images/" | relative_url %}
[![{{include.create_type | capitalize}} Overview]({{src}}){:.w-50}]({{src}})
{:.text-center}

{{include.create_type | capitalize}}s can be categorized into **Flex {{include.create_type | capitalize}}s** and **User {{include.create_type | capitalize}}s**.

## Flex {{include.create_type | capitalize}}s

Flex {{include.create_type | capitalize}}s are {{include.create_type}}s built into Flex by default and cannot be modified. They are the starting point of {{include.create_type}} customization.

## User {{include.create_type | capitalize}}s

User {{include.create_type | capitalize}}s are modifiable {{include.create_type}}s created by the user. They are stored locally on the device. If you use Clear Data on the app, all User {{include.create_type | capitalize}}s will be deleted.


## Create a New {{include.create_type | capitalize}}

To create a new {{include.create_type}}, 
1. Click on the **More** button on the right of an existing {{include.create_type}}. 
2. Then click on **Duplicate**. 
3. This will create a new User {{include.create_type | capitalize}}. You may need to scroll to the top to see it.
4. Click on the User {{include.create_type | capitalize}} to begin customizing.

{% assign src=include.create_type | append: "_duplicate.png" | prepend: "/assets/images/" | relative_url %}
[![Create New {{include.create_type | capitalize}}]({{src}}){:.w-50}]({{src}})
{:.text-center}

## Rename {{include.create_type | capitalize}} & Description

The new {{include.create_type}}'s name & description can be changed to your liking.
1. Click on the **More ** button on the right.
2. Then click on **Rename**.
3. Click on the property you would like to change.

{% include gallery.md data = include.rename_images %}

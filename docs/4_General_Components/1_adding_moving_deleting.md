---
sort: 1
---

# Adding / Moving / Removing

<iframe class="vimeo_player" width="1280" height="720" src="https://player.vimeo.com/video/528254297?autoplay=0&loop=1&quality=1080p" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

This component deals with all pages and modules that offer the functionality to add, move or remove an item. For example, you can find it at the top the 'Menu and Navigation' section, and it looks like this:

![Image of Menu Items, within Menu and Navigation](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/4_General_Components/images/general_components_nav_example.png)


## On Mobile

All of our components have a slightly different look on mobile devices. This is necessary due to the limited screen size available on mobiles. We never remove any functionality, meaning the website builder stays just as functional on mobile as it is on desktop, but things will shift around to accommodate this:

![Image of Menu Items, within Menu and Navigation, for advanced users, on mobile](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/4_General_Components/images/general_components_nav_example_mobile.png)


## Adding

![Image of the add / move / remove component, 'add' highlighted](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/4_General_Components/images/general_components_nav_example_add_highlighted.png)

Selecting the 'Add' button will immediately create a new list item, which will not have any information pre-filled. Most of the time, this item will not be shown by the website builder until its most essential information has been filled in.

## Moving

![Image of the add / move / remove component, 'move' highlighted](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/4_General_Components/images/general_components_nav_example_move_highlighted.png)

Selecting the 'Move' button will create moving handles on the right of any list item, like so:

![Image of the add / move / remove component, 'move' highlighted](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/4_General_Components/images/general_components_moving_handle.png)

This simultaneously disables all editing functionality for the item, as well as the other functions of the component, such as 'add' or 'delete'.

Moving items is done by selecting (and holding) the draggable handle and moving the list item to the new desired position.

You may accept your changes by selecting the 'back' button:

![Image of the add / move / remove component, 'move' highlighted](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/4_General_Components/images/general_components_move_back_button.png)

```tip
Your changes have not been saved yet. This only happens once you select one of the [save](https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/3_bottom_bar_modules.html#saving-changes) buttons.
```

## Removing

![Image of the add / move / remove component, 'remove' highlighted](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/4_General_Components/images/general_components_nav_example_remove_highlighted.png)

The 'Delete' button will create checkboxes to the right of any list item, like so:

![Image of the 'delete' checkbox within the add / move / delete states](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/4_General_Components/images/general_components_delete_checkbox.png)

In this state, all other editing functions are disabled.

Before you have selected any items, the 'delete' button will remain greyed out and unavailable:

![Image of the 'delete' state, with delete greyed out](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/4_General_Components/images/general_components_delete_greyed_out.png)

You may also choose to go back via the back button (as shown above).

You may also select all items using the 'select all' checkbox:

![Image of the 'delete' state, delete all checkbox](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/4_General_Components/images/general_components_delete_all.png)

Once you have chosen your items to delete, select the (now enabled) delete button:

![Image of the 'delete' state, delete enabled](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/4_General_Components/images/general_components_delete_enabled.png)

```danger
The website builder will not warn you before deleting list items, so make sure you really want to delete them
```
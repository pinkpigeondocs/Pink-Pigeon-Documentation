---
sort: 2
---

# Picking Images

Image pickers come in a few varieties. One of the most common ones is the standalone image picker component. For example, the 'Logo' picker within 'Menu and Navigation':

![Image of logo, within Menu and Navigation](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/5_Pages/images/nav_logo.png)

Another image picker exists within list items, such as the Price List module:

![Image of logo, within Menu and Navigation](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/4_General_Components/images/general_components_price_list_image_example.png)

As you can see, their design matches closely, as does their functionality. Thus, even with components being in different places, we will always strive to keep them recognisable and all functionality the same.

## Changing an image

When you click anywhere on the image (not just the circular icon in the lower right), the image gallery overlay opens, allowing you to select a new image. This is what the image gallery overlay looks like:

![Image of the up-arrow for file uploads](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/common_elements_images/image_library_overlay.png)

If you had already selected an image previously, this image will be highlighted with a pink outline. If not, then clicking any image will add the pink outline, marking it as selected for insertion. When you select the 'Insert'-button, the image you selected replaces the one that was shown in the component before.

```tip
Just selecting a new image does not save your change. You still have to select one of the ['save'][save] buttons at the bottom of the page. This will make the new image show up in your preview site.
```

## Uploading a new image

From within the image library overlay, you may also upload images directly. To do this, you need to select the 'add' button:

![Image of the add button within the image gallery overlay](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/4_General_Components/images/image_library_overlay_add_button.png)

This will open a file browser (which will be different for every operating system / device), where you may select an image up to 2MB big. We support .JPG, .SVG, .GIF and .PNG images. Any image above 512kb will be compressed, to ensure your website stays fast for your visitors.

[save]: https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/3_bottom_bar_modules.html#saving-changes
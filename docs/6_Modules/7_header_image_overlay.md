---
sort: 7
---

# Header (Image Overlay)

<iframe class="vimeo_player" width="1280" height="720" src="https://player.vimeo.com/video/552061838?autoplay=0&loop=1&quality=1080p" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

![Image of the header-image module online](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_image_online.png)

The header is a slightly more complex module. It allows for the displaying of two background images, one for mobile, one for desktop resolutions (as this may work better than trying to make just one image fit such different screen sizes), though this is not mandatory.

The background can also be a 16:9 (and 9:16 for mobile) video (from vimeo only, as they allow removal of UI elements with their embedded videos).

Additionally, another image can be uploaded to be displayed on top of the background images, such as a company logo. The overlay-image's position can be customised deeply.

The mobile version of the header allows for three different image heights, depending on the best content fit.

The header is traditionally the first module on a page with a header, but could be placed anywhere on a site also.

## Enabling / Disabling

Like all modules, this module can be enabled / disabled. Please see the [corresponding section of the documentation][endis] to find out more about this functionality.

[endis]: https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/4_enabling_disabling_modules.html

## Background Section (Video)

When the background Image / Video option has been set to 'video', the following options appear:

### Video Scale (Mobile)

This option allows you to scale the video player up (in other words, to 'zoom' into the video). This can help eliminate letterboxing (or black bars around the video), in case the video doesn't quite fit the space.
There is a mobile and desktop option for the video, to make it easier to avoid having to use this option much.
If, for example, you have only been supplied with a portrait-orientation video, you'll need a zoom factor of 3.2 for the desktop video, for it to fill the whole space.

### Video Scale (Desktop)

Same as the video scale for mobile.

### Video ID (Mobile)

The Vimeo video ID of your video on mobile. Find out how you can get that ID here.

This video should be 9:16 (portrait) aspect ratio. So that's 2160x3840 in 4K, 1080x1920p in full HD or 720x1280p in just HD.

### Video ID (Desktop)

The Vimeo video ID of your video on desktop. Find out how you can get that ID here.

This video should be 16:9 (landscape) aspect ratio. So that's 3840x2160 in 4K, 1920x1080p in full HD or 1280x720p in just HD.

## Background Section (Image)

When the background Image / Video option has been set to 'image', the following options appear:

### Desktop Image

![Image of the header desktop image](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_desktop_image.png)

The header module's background image on desktop. This image will be shown at screen resolutions of 900px and above, typically laptops and desktop computers.
Read up on changing images [here](https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/2_image_picker.html).

### Double Desktop Image

<iframe class="vimeo_player" width="1280" height="720" src="https://player.vimeo.com/video/552059803?autoplay=0&loop=1&quality=1080p" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

![Image of the header desktop double image](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_double_image.png)

There is a double-image variation of this header, where two images can be used as the background to a header, sitting side by side.
Read up on changing images [here](https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/2_image_picker.html).

### Mobile Image

![Image of the header mobile image](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_mobile_image.png)

The header module's background image on mobile. This option allows you to specify an image that is shown below 900px screen width (mobile / tablet devices). It is not necessary to define a different image here. In our example, we have decided to use the same background twice. In some cases, however, it can be beneficial to provide content for mobile devices that fits the space better. This is often a question of experimentation, to arrive at the best solution for your website.
Read up on changing images [here](https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/2_image_picker.html).

## Overlay Element

The overlay element sits on top of the header's background image:

![Image of the image overlay of the header module, image overlay type, online](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_image_overlay_highlighted_online.png)

## Enabling the Overlay

![Image of the header option to enable overlay](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_enable.png)

Here, the overlay can be switched on or off.

**on**

![Image of the header-image module with overlay on online](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_width_20_percent.png)

**off**

![Image of the header-image module with overlay off online](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_off_online.png)

## Overlay Image

![Image of the header overlay image option](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_image.png)

The header module's overlay image. Read up on changing images [here](https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/2_image_picker.html).
For overlay images it is recommended to use image formats that support transparency, such as .PNG, .GIF or .SVG. (Our example uses a .PNG image)
Overlaying an image with a filled block-colour type background would not look as well-designed.

## Overlay Position

![Image of the header overlay position option](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_position.png)

The overlay can be placed in any 9 sectors of the header. Please note that on mobile, left / right placements are replaced with a central placement. Thus, only top / middle / bottom placements are taken into account on mobile. This is due to the narrow screen widths of mobile devices.

**Left Middle Placement Example**

![Image of the header overlay position option, left middle](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_left.png)

**Left Middle Placement Online**

![Image of the header overlay position option, left middle](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_left_online.png)

## Overlay Width - Desktop

![Image of the header overlay width option](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_width.png)

This determines the maximum width of the image overlaid on top of the header's background image (as percentage of the total screen width). The height of the overlay image will scale automatically, preserving the aspect ratio (i.e. your image will never be skewed by adjusting this value)

**20% Example**

![Image of the header overlay width option at 20 percent](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_width_20_percent.png)

**60% Example**

![Image of the header overlay width option at 60 percent](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_width_60_percent.png)

## Overlay Width - Mobile

![Image of the header overlay width mobile option](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_width_mobile.png)

The overlay image can have a different width on mobile, as we have found that the smaller screen-sizes of mobile devices need special consideration, especially for finely detailed graphics.

## Overlay Side Margin

![Image of the header overlay side margin option](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_side_margin.png)

This determines how far the overlay image will be from the edge of the screen (as percentage of the total screen width) when you have chosen one of the left or right squares in the overlay position section.

**0% Example**

![Image of the header overlay side margin option at 0 percent](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_side_margin_0_percent.png)

**10% Example**

![Image of the header overlay side margin option at 10 percent](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_side_margin_10_percent.png)

## Overlay Top Margin

![Image of the header overlay top margin option](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_top_margin.png)

This determines how far the overlay image will be from the top / bottom of the screen when you have chosen one of the top / bottom squares in the overlay position section.
**Note:** This value is in **pixels**, not percent, due to the way websites position elements. The side margin / width values are percentages of the screen width.

**15px Example**

![Image of the header overlay top margin option - 15px](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_top_margin_15px.png)

**50px Example**

![Image of the header overlay top margin option - 50px](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_top_margin_50px.png)

## Tint Colour

![Image of the header overlay tint colour option](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_tint_colour.png)

If your tint opacity is higher than 0, you may choose the colour of the tint to apply to the background image. This feature exists, as some graphics need additional contrast to the background they sit on top of. Here, you can define a tint colour to 'knock back' the background image, giving more emphasis to the overlay.

**Green Tint Example:**

![Image of the header overlay tint colour option in green](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_tint_colour_green.png)

## Tint Opacity

![Image of the header overlay tint opacity option](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_tint_opacity.png)

This determines whether you would like to apply a tint to the background image. In our example, we have chosen a black tint at 0.4 opacity (maximum is 1, minimum is 0, i.e. no tint), to 'fade' the background somewhat, giving more contrast to the overlaid logo.

**0.4 Example**

![Image of the header overlay tint opacity at 0.4](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_tint_opacity_0_point_4.png)

**0.8 Example**

![Image of the header overlay tint opacity at 0.8](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_tint_opacity_0_point_8.png)

## Mobile Image Shape

![Image of the header mobile image shape option](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_mobile_image_shape.png)

Because mobile devices have such a wide range of screen sizes, and there is such a variety of imagery that could be used with the header, we allow for three different aspect ratios of header images below 900px screen width (which is a typical phone / tablet resolution).

**Portrait Example**

![Image of the header mobile image shape Portrait option](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_mobile_image_shape_portrait_online.png)

**Square Example**

![Image of the header mobile image shape Square option](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_mobile_image_shape_square_online.png)

**Landscape Example**

![Image of the header mobile image shape Landscape option](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_mobile_image_shape_landscape_online.png)

## Mobile Background

![Image of the header mobile background option](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_mobile_background.png)

If the mobile image shape option is set to either Landscape or Square, the "Mobile Background" option appears. With Landscape or Square mobile image shapes, the image overlay moves below the (mobile) header background image, into its own area with a customisable background colour.

## Chevron Options

![Image of the header chevron options](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_chevron_options.png)

The header chevron is a clickable item, which automatically moves the page down to the module below the header.
The chevron is displayed for the following configurations:

Mobile image shape: Portrait on desktop and mobile
Mobile image shape: Square on desktop only
Mobile image shape: Landscape on desktop only

This is the chevron:

![Image of the header chevron online](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_chevron_online.png)

The chevron colour and rollover (when a visitor hovers over the chevron, this is the colour it will be) colour can be customised as well.


```tip
Please do not forget to hit one of the [save](https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/3_bottom_bar_modules.html#saving-changes) buttons, to make sure the changes you have made are actually saved. Why not keep a window with your [preview](https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/7_Previews/) open, to see the changes in realtime?
```
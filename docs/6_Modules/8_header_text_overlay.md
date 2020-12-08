---
sort: 8
---

# Header (Text Overlay)

![Image of the header-text module online](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/8_header_text_online.png)

The header is a slightly more complex module. It allows for the displaying of two images, one for mobile, one for desktop resolutions (as this may work better than trying to make just one image fit such different screen sizes), though this is not mandatory.

Additionally, text can be displayed on top of the background images, such as a company tag-line. The overlay-text's position can be customised deeply.

The mobile version of the header allows for three different image heights, depending on the best content fit.

The header is traditionally the first module on a page with a header, but could be placed anywhere on a site also.

## Enabling / Disabling

Like all modules, this module can be enabled / disabled. Please see the [corresponding section of the documentation][endis] to find out more about this functionality.

[endis]: https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/4_enabling_disabling_modules.html

## Desktop Image

The header module's desktop image. Read up on changing images [here](https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/2_image_picker.html).

## Vertical Alignment

Because many images may not fit perfectly into the space reserved for them, you can control the vertical alignment, 'sliding' the image up or down within its space. Here is an example. Here is an example at 0% (Or "image should sit as far down as possible within its space):

![Image of the image panel of a text and image module at 0% alignment](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/12_text_and_image_0_percent.png)

Here is an example at 100% (Or "image should sit as high up as possible within its space):

![Image of the image panel of a text and image module at 100% alignment](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/12_text_and_image_100_percent.png)

You may notice the locks in the image have moved up.

## Mobile Image

The header module's mobile image. Read up on changing images [here](https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/2_image_picker.html).

## Vertical Alignment

See the section above, describing this.

## Overlay Element

The overlay element sits on top of the image.

## Enabling the Overlay

![Image of the header option to enable overlay](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_enable.png)

Here, the overlay can be switched on or off.

**on**

![Image of the header-image module online](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_overlay_off_online.png)

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

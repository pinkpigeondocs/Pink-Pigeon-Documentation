---
sort: 7
---

# Header (Image Overlay)

![Image of the header-image module online](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_image_online.png)

The header is a slightly more complex module. It allows for the displaying of two images, one for mobile, one for desktop resolutions (as this may work better than trying to make just one image fit such different screen sizes), though this is not mandatory.

Additionally, another image can be uploaded to be displayed on top of the background images, such as a company logo. The overlay-image's position can be customised deeply.

Lastly, the mobile version of the header allows for three different image heights, depending on the best content fit.

## Enabling / Disabling

Like all modules, this module can be enabled / disabled. Please see the [corresponding section of the documentation][endis] to find out more about this functionality.

[endis]: https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/4_enabling_disabling_modules.html

## Desktop Image

![Image of the header desktop image](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_desktop_image.png)

The header module's background image on desktop. This image will be shown at screen resolutions of 900px and above, typically laptops and desktop computers.
Read up on changing images [here](https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/2_image_picker.html).

## Vertical Alignment

![Image of the vertical alignment option](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/common_elements_images/vertical_alignment.png)

Because many images may not fit perfectly into the space reserved for them, you can control the vertical alignment, 'sliding' the image up or down within its space. Here is an example. Here is an example at 0% (Or "image should sit as far down as possible within its space):

![Image of the image panel of a text and image module at 0% alignment](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/12_text_and_image_0_percent.png)

Here is an example at 100% (Or "image should sit as high up as possible within its space):

![Image of the image panel of a text and image module at 100% alignment](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/12_text_and_image_100_percent.png)

You may notice the locks in the image have moved up.

## Mobile Image

The header module's background image on mobile. This option allows you to specify an image that is shown below 900px screen width (mobile / tablet devices). It is not necessary to define a different image here. In our example, we have decided to use the same background twice. In some cases, however, it can be beneficial to provide content for mobile devices that fits the space better. This is often a question of experimentation, to arrive at the best solution for your website.
Read up on changing images [here](https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/2_image_picker.html).

## Vertical Alignment (mobile)

![Image of the vertical alignment option](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/common_elements_images/vertical_alignment.png)

This is the same option as [above](https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/6_Modules/7_header_image_overlay.html#vertical-alignment), but for mobile images.

## Overlay Element

The overlay element sits on top of the header's background image:

![Image of the image overlay of the header module, image overlay type, online](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/7_header_image_overlay_highlighted_online.png)

## Enabling the Overlay

The overlay can be switched on or off

## Overlay Image

The header module's overlay image. Read up on changing images [here](https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/2_image_picker.html).
For overlay images it is recommended to use image formats that support transparency, such as .PNG, .GIF or .SVG. (Our example uses a .PNG image)
Overlaying an image with a filled block-colour type background would not look as well-designed.

## Overlay Position

The overlay can be placed in any 9 sectors of the header. Please note that on mobile, left / right placements are replaced with a central placement. Thus, only top / middle / bottom placements are taken into account on mobile. This is due to the narrow screen widths of mobile devices.

## Overlay Width - Desktop

This determines the maximum width of the image overlaid on top of the header's background image. The height of the overlay image will scale automatically, preserving the aspect ratio (i.e. your image will never be skewed by adjusting this value)

## Overlay Width - Mobile

The overlay image can have a different width on mobile, as we have found that the smaller screen-sizes of mobile devices need special consideration, especially for finely detailed graphics.

## Overlay Side Margin

This determines how far the overlay image will be from the edge of the screen when you have chosen one of the left or right squares in the overlay position section.

## Overlay Top Margin

This determines how far the overlay image will be from the top / bottom of the screen when you have chosen one of the top / bottom squares in the overlay position section.

## Tint Colour

If your tint opacity is bigger than 0, you may choose the colour of the tint to apply to the background image. This feature exists, as some graphics need additional contrast to the background they sit on top of. Here, you can define a tint colour to 'knock back' the background image, giving more emphasis to the overlay.

## Tint Opacity

This determines whether you would like to apply a tint to the background image. In our example, we have chosen a black tint at 0.4 opacity (maximum is 1, minimum is 0, i.e. no tint), to 'fade' the background somewhat, giving more contrast to the overlaid logo.
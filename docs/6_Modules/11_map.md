---
sort: 11
---

# Map

![Image of the image map module online](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/11_map_online.png)

The Map module lets you add a map to your site. There is a [grid](https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/7_grids.html) variant of this module.

## Enabling / Disabling

Like all modules, this module can be enabled / disabled. Please see the [corresponding section of the documentation][endis] to find out more about this functionality.

[endis]: https://pinkpigeondocs.github.io/Pink-Pigeon-Documentation/4_General_Components/4_enabling_disabling_modules.html

## Map Link

![Image of the image map module link](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/11_map_link.png)

This is the link to your Google Maps 'embed'. These are the steps to get it:

- **Go to [www.google.com/maps/](https://www.google.com/maps/)**

![Image of google maps](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/11_map_google_maps_first.png)


- **Find the location you would like to add**

![Image of google maps, search term entered](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/11_map_google_maps_search.png)


- **Click on the location, so you see this screen**
![Image of google maps, search complete](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/11_map_search_complete.png)


- **Click on 'Share'**
![Image of google maps, share highlighted](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/11_map_share_highlighted.png)


- **Click on 'Embed a map'**
![Image of google maps embed](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/11_map_share_embed_highlighted.png)


- **Click 'COPY HTML'**
![Image of google maps, copy html highlighted](https://raw.githubusercontent.com/pinkpigeondocs/Pink-Pigeon-Documentation/master/docs/6_Modules/images/11_map_copy_html.png)


- **Selecting just the link part of the HTML**


This is just the part in double quotes behind the '=' sign after 'src'. So, if your link looks like this:

```<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d5907.839785455565!2d-0.17920472437411206!3d51.49595662440386!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x48760542e6182f3f%3A0x7bb7e385c39764c4!2sNatural%20History%20Museum!5e0!3m2!1sen!2suk!4v1607516254069!5m2!1sen!2suk" width="600" height="450" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>```

You should only take: ```https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d5907.839785455565!2d-0.17920472437411206!3d51.49595662440386!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x48760542e6182f3f%3A0x7bb7e385c39764c4!2sNatural%20History%20Museum!5e0!3m2!1sen!2suk!4v1607516254069!5m2!1sen!2suk``` from it.

- **Copy this back into the module's Map Link field and hit 'save'**


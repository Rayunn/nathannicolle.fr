=== WP Slick Slider and Image Carousel ===
Contributors: wponlinesupport, anoopranawat, pratik-jain, mehulwpos, jahnavwponlinesupport, rafikwp
Tags: slick, image slider, slick slider, slick image slider, slider, image slider, header image slider, responsive image slider, responsive content slider, carousel, image carousel, carousel slider, content slider, coin slider, touch slider, text slider, responsive slider, responsive slideshow, Responsive Touch Slider, wp slider, wp image slider, wp header image slider, photo slider, responsive photo slider  
Requires at least: 4.0
Tested up to: 5.9.2
Stable tag: 3.0.9
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

A quick, easy way to add and display mulipale WP Slick Slider and carousel using a shortcode. Also added Gutenberg block support.

== Description ==

[Explore Slick Slider Pro Features](https://www.essentialplugin.com/wordpress-plugin/wp-slick-slider-and-image-carousel/?utm_source=WP&utm_medium=Slick-Slider&utm_campaign=Read-Me) | [Bundle Deal](https://www.essentialplugin.com/wordpress-plugin/wp-slick-slider-and-image-carousel/?utm_source=WP&utm_medium=Slick-Slider&utm_campaign=Read-Me#wpos-epb)

[WP Slick Slider and Image Carousel](https://www.essentialplugin.com/wordpress-plugin/wp-slick-slider-and-image-carousel/?utm_source=WP&utm_medium=Slick-Slider&utm_campaign=Read-Me) is one of the leading & popular Slick Slider plugins available for WordPress.

Display multiple slick image slider and carousel using shortcode with category. Fully responsive, Swipe enabled, Desktop mouse dragging and  Infinite looping. Fully accessible with arrow key navigation  Autoplay, dots, arrows etc.

= Features =
[youtube https://www.youtube.com/watch?v=yTfbOaYJYR0] 

It uses A custom post type and taxonomy to create a slider, with almost unlimited options and support for multiple sliders on any page. You can also display image slider on your website header.

We have added 5 designs for slider and 1 design for carousel. You can find all designs on our demo website. Just copy the shortcode of design that you like and use.

**Also added Gutenberg block support.**

= You can use 2 shortcodes =

<code>[slick-slider] and [slick-carousel-slider]</code>

= Here is Template code =

<code><?php echo do_shortcode('[slick-slider]'); ?>  and
 <?php echo do_shortcode('[slick-carousel-slider]'); ?> </code>

= Use Following parameters with shortcode =

<code>[slick-slider]</code>

* **limit** : [slick-slider limit="-1"] (Limit define the number of images to be display at a time. By default set to "-1" ie all images. eg. if you want to display only 5 images then set limit to limit="5")
* **category**: [slick-slider category="category_ID"] ( ie Display slider by their category ID ).
* **show_content** : [slick-slider show_content="true" ] (Display content OR not. By default value is "true". Options are "true OR false").
* **Pagination and arrows** : [slick-slider dots="false" arrows="false"]
* **Autoplay and Autoplay Interval**: [slick-slider autoplay="true" autoplay_interval="100"]
* **Slide Speed**: [slick-slider speed="3000"]
* **fade** : [slick-slider fade="true" ] (Slider Fade effect. By default effect is slide. If you set fade="true" then effect change from slide to fade ).
* **lazyload** : [slick-slider lazyload="ondemand" ] (Use lazyload with slick slider. By default there is no lazyload enabled. If you want to set lazyload then use lazyload="ondemand" OR lazyload="progressive" ).
* **loop** : [slick-slider loop="true"] (Create a Infinite loop sliding. By default value is "true". Options are "true" OR "false".)
* **hover_pause** : [slick-slider hover_pause="true"] (Pause slider autoplay on hover. By default value is "true". Options are "true" OR "false".)
* **image_size** : [slick-slider image_size="full"] (Default is "full", values are thumbnail, medium, medium_large, large, full)
* **image_fit** : [slick-slider image_fit="false"] (image_fit parameter is used to specify how an image should be resized to fit its container. By default value is "false". Options are "true OR false"). NOTE :  image_fit="true" work better if sliderheight is given. if image_fit="false", no need to use sliderheight parameter.
* **sliderheight** : [slick-slider sliderheight="400" ] (Set image wrap height. NOTE : This parameter work better if image_fit="true" ).
* **rtl** : [slick-slider rtl="true"] (for rtl mode. By default value is "false". Options are "true OR false").

= Use Following parameters with shortcode =

<code>[slick-carousel-slider]</code>

* **limit** : [slick-carousel-slider limit="-1"] (Limit define the number of images to be display at a time. By default set to "-1" ie all images. eg. if you want to display only 5 images then set limit to limit="5")
* **design** : [slick-carousel-slider design="design-1"] (You can select 5 design( design-1, design-2, design-3, design-4, design-5 ) for your  slider. Slick Slider -> Slider Designs ).
* **category**: [slick-carousel-slider category="category_ID"] ( ie Display slider by their category ID ).
* **image_size** : [slick-carousel-slider image_size="full"] (Default is "full", values are thumbnail, medium, medium_large, large, full)
* **slidestoshow** : [slick-carousel-slider slidestoshow="3" ] (Display number of images at a time. By default value is "3").
* **slidestoscroll** : [slick-carousel-slider slidestoscroll="1" ] (Scroll number of images at a time. By default value is "1").
* **Pagination and arrows** : [slick-carousel-slider dots="false" arrows="false"]
* **Autoplay and Autoplay Interval**: [slick-carousel-slider autoplay="true" autoplay_interval="100"]
* **loop** : [slick-carousel-slider loop="true"] (Create a Infinite loop sliding. By default value is "true". Options are "true" OR "false".)
* **hover_pause** : [slick-carousel-slider hover_pause="true"] (Pause slider autoplay on hover. By default value is "true". Options are "true" OR "false".)
* **Slide Speed**: [slick-carousel-slider speed="3000"]
* **lazyload** : [slick-carousel-slider lazyload="ondemand" ] (Use lazyload with slick slider. By default there is no lazyload enabled. If you want to set lazyload then use lazyload="ondemand" OR lazyload="progressive" ).
* **centermode** : [slick-carousel-slider centermode="true" ] ( Display main image on center. By default value is "false" ).
* **variablewidth** : [slick-carousel-slider variablewidth="true" ] (Variable width of images in slider. By default value us "false")
* **image_fit** : [slick-carousel-slider image_fit="false" ] (image_fit parameter is used to specify how an image should be resized to fit its container. By default value is "false". Options are "true OR false"). NOTE :  image_fit="true" work better if sliderheight is given. if image_fit="false", no need to use sliderheight parameter.
* **sliderheight** : [slick-carousel-slider sliderheight="400" ] (Set image wrap height. NOTE : This parameter work better if image_fit="true" ).
* **rtl** : [slick-carousel-slider rtl="true"] (for rtl mode. By default value is "false". Options are "true OR false").

**Note: Due to lots of feedback from your users side, we have made image_fit="false" by default. Previously it was image_fit="true". We made image resize option now optional. If you want to resize the image, please use image_fit="true" and sliderheight="400" (400 is just an example. Please use this value as per your need) shortcode parameters.**

= PRO Features Added : =
> <strong>Premium Version</strong><br>
>
> * 90+ Predefined stunning designs.
> * 30 Image Slider Designs.
> * 30 Image Carousel and Center Slider Designs.
> * 33 Slider Variable width Designs.
> * Gutenberg Block Supports.
> * WP Templating Features.
> * WPBakery Page Builder Support.
> * Elementor, Beaver and SiteOrigin Page Builder Native Support (New).
> * Divi Page Builder Native Support (New).
> * Fusion Page Builder (Avada) Native Support (New).
> * Drag & Drop frature to display slide in your order.
> * Custom CSS plugin setting option.
> * Powerful shortcode with strong parameters.
> * Display content with image and link in Carousel mode .  
> * Fully Responsive.
> * 100% Multi Language.
>
> [Explore WP Slick Slider and Image Carousel Pro Features](https://www.essentialplugin.com/wordpress-plugin/wp-slick-slider-and-image-carousel/?utm_source=WP&utm_medium=Slick-Slider&utm_campaign=Read-Me)
>

Find out about other [best WordPress plugins](https://www.essentialplugin.com/wordpress-plugins/).

= How to install : =
[youtube https://www.youtube.com/watch?v=rkbohcgmzVg] 

= Features include =

* Also added Gutenberg block support.
* Display unlimited number of slider and carousel with the help of category.
* Touch-enabled Navigation.
* Fully responsive. Scales with its container.
* Fully accessible with arrow key navigation.
* Responsive
* Given shortcode and template code.
* Use for header image slider.

= Privacy & Policy =
* We have also opt-in e-mail selection , once you download the plugin , so that we can inform you and nurture you about products and its features.

== Installation ==

1. Upload the 'wp-slick-slider-and-carousel' folder to the '/wp-content/plugins/' directory.
2. Activate the "wp-slick-slider-and-carousel" list plugin through the 'Plugins' menu in WordPress.
3. Add this short code where you want to display slider

<code>[slick-slider] and [slick-carousel-slider]</code>

= How to install : =
[youtube https://www.youtube.com/watch?v=rkbohcgmzVg] 

== Screenshots ==

1. Design-1
2. Design-2
3. Design-3
4. Design-4
5. Design-5
6. Design-6
7. Also work with Gutenberg shortcode block.
8. Also added Gutenberg block support.
9. Also added Gutenberg block support.

== Changelog ==

= 3.0.9 (29, March 2022) =
[+] Added free vs pro functionality.
[+] Tested up to: 5.9.2

= 3.0.8 (10, March 2022) =
* [+] Added demo link
* [-] Removed some unwanted code and files.

= 3.0.7 (11, Feb 2022) =
* [-] Removed some unwanted code and files.

= 3.0.6 (07, Feb 2022) =
* [*] Tested up to: 5.9 
* [*] Fixed some small issues.

= 3.0.5 (03, Feb 2022) =
* [*] Tested up to: 5.9 
* [*] Solved Gutenberg wp-editor widget issue.

= 3.0.4.1 (15, Dec 2021) =
* [*] Minor fix.

= 3.0.4 (12, Nov 2021) =
* [*] Fix - Resolve Gutenberg WP-Editor script related issue. 
* [*] Update - Add some text and links in Readme file.

= 3.0.3 (26, Oct 2021) =
* [*] Fixed a variable prefix name issue.

= 3.0.2.1 (16, Sep 2021) =
* [*] Fixed some small issue with DIVI theme
* [*] Fixed a variable name issue.

= 3.0.2 (15, Sep 2021) =
* [*] Tested up to: 5.8.1
* [*] Updated Demo Link.

= 3.0.1 (18, Aug 2021) =
* [*] Updated language file and json file.
* [*] Updated plugin analytics code.

= 3.0 (17, Aug 2021) =
* [*] Updated all external links
* [*] Tweak - Code optimization and performance improvements.
* [*] Fixed Blocks Initializer Issue.

= 2.4.3 (31, May 2021) =
* [*] Tested up to: 5.7.2
* [*] Added - https link in our analytics code to avoid browser security warning.

= 2.4.2 (24, May 2021) =
* [*] Tested up to: 5.7.2
* [*] Tweak - Code optimization and performance improvements.

= 2.4.1 (3, May 2021) =
* [*] Tested up to: 5.7.1
* [*] solve extra_class parameter issue. 

= 2.4 (15, March 2021) =
* [*] Tested up to: 5.7

= 2.3 (25, jan 2021) =
* [+] New - Added native shortcode support for Elementor, SiteOrigin and Beaver builder.
* [+] New - Added Divi page builder native support.
* [+] New - Added Fusion Page Builder (Avada) native support.
* [*] Tweak - Code optimization and performance improvements.

= 2.2.1 (27, Oct 2020) =
* [*] Minor  Update - Fixed conflict from tgmpa (theme pluign recommends - if your theme using tgmpa library) where it was showing message inside "How It Works - Display and shortcode"

= 2.2 (22, Oct 2020) =
* [+] New - Click to copy the shortcode from the getting started page.
* [*] Update - Regular plugin maintenance. Updated readme file.
* [*] Added - Added our other Popular Plugins under Slick Slider --> Install Popular Plugins From WPOS. This will help you to save your time during creating a website.

= 2.1 (14, Aug 2020) =
* [*] jQuery( document ).ready(function($) is replaced with function( $ ) to solve the issue with 3rd party plugin and theme js error.

= 2.0.2 (14-07-2020) =
* [*] Follow WordPress Detailed Plugin Guidelines for Offload Media and Analytics Code.

= 2.0.1 (07, July 2020) =
* [*] Due to lots of feedback from your users side, we have made image_fit="false" by default. Previously it was image_fit="true". We made image resize option now optional. If you want to resize the image, please use image_fit="true" and sliderheight="400" (400 is just an example. Please use this value as per your need) shortcode parameters.
* [*] Fixed some design related issues.
* [*] Tested up to: 5.4.2

= 2.0 (17, April 2020) =
* [+] New - Added Gutenberg block support. Now use plugin easily with Gutenberg!
* [+] New - Added 'align' and 'extra_class' parameter for slider shortcode. Now both slider shortcode are support twenty-ninteent and twenty-twenty theme gutenberg block align and additional class feature.
* [+] New - Add new classes sanatize function in function file.
* [*] Tweak - Code optimization and performance improvements.

= 1.9.3 (06, April 2020) =
* [+] Added new shortcode parameter loop and hover_pause for both shortcode
* [+] loop  : Create a Infinite loop sliding. By default value is "true". Options are "true" OR "false".
* [+] hover_pause  : Pause slider autoplay on hover. By default value is "true". Options are "true" OR "false".

= 1.9.2 (05, March 2020) =
* [+] Added new shortcode parameter lazyload="ondemand" OR lazyload="progressive" for both shortcodes.

= 1.9.1 (26, Dec 2019) =
* [*] Updated features list.
* [*] Replaced wp_reset_query() with wp_reset_postdata()
* [*] Added prefix wpsisac- to all classes in css to avoid conflict with any theme and third-party plugins.

= 1.8 (08, August 2019) =
* [*] Update demo links
* [*] Fixed some small-small issues.
* [*] Updated text under featred image ie Add slider image.

= 1.7.1 (31, May 2019) =
* [+] Added new shortcode parameter ie image_fit="true". image_fit parameter is used to specify how an image should be resized to fit its container. By default value is "true". Options are "true OR false". NOTE : NOTE :  image_fit="true" work better if sliderheight is given. if image_fit="false", no need to use sliderheight parameter.  
* [*] image_fit parameter work with both the shortcode.
* [+] Added new shortcode parameter ie image_size="full" for shortcode [slick-slider] (Default is "full", values are thumbnail, medium, medium_large, large, full)
* [-] Removed default height 400 from sliderheight parameter.
* [-] Remove object-fit CSS property from img under CSS if image_fit="false".

= 1.6.2 (12, Feb 2019) =
* [*] Minor change in Opt-in flow.

= 1.6.1 (26, Dec 2018) =
* [*] Update Opt-in flow.

= 1.6 (06, Dec 2018) =
* [*] Tested with WordPress 5.0 and Gutenberg.
* [*] Fixed slider height issues with some designs.
* [*] Taken better security with `esc_url` and `esc_html`. 
* [*] Fixed some CSS issues.

= 1.5.1 (05, June 2018) =
* [*] Follow some WordPress Detailed Plugin Guidelines.

= 1.5 (10/3/2018) =
* [*] Fixed  some css issues related to slider arrow.

= 1.4 (10/3/2018) =
* [*] Fixed  some css issues

= 1.3.4 (04/10/2017) =
* [*] Fixed all responsive issues and checked many mobile devices.
* [*] If you are using any cache plugin, please clear your cacheing after plugin updates

= 1.3.3 (04/10/2017) =
* [*] Updated slick.min.js to the latest version
* [*] Fixed all responsive issues and checked many mobile devices.
* [*] If you are using any cache plugin, please clear your cacheing after plugin updates

= 1.3.2.1 (27/09/2017) =
* [*] Fixed design-6 issue with shortcode parameter variablewidth="true" in responsive layout
* [*] If you are using any cache plugin, please clear your cacheing after plugin updates

= 1.3.2 (23/09/2017) =
* [*] Fixed design-6 issue with shortcode parameter variablewidth="true"
* [*] If you are using any cache plugin, please clear your cacheing after plugin updates 

= 1.3.1.1 (23/09/2017) =
* [*] Fix responsive issue reported by users in v-1.3.1 
* [*] If you are using any cache plugin, please clear your cacheing after plugin updates 

= 1.3.1 (22/09/2017) =
* [*]  Fix main JS wp_register_script issue

= 1.3 (22/09/2017) =
* [+] Added **sliderheight** parameter in shortcode <code>[slick-carousel-slider]</code>
* [*] RTL made better to work with RTL websites
* [*] Center mode and variablewidth improved better as per usres feedback 
* [*]  **sliderheight** parameter improved

= 1.2.8 (22/05/2017) =
* [+] RTL Supported

= 1.2.7 (25/04/2017) =
* [+] Added overlay for design-2

= 1.2.6 (07/11/2016) =
* [+] Added "How it work tab"
* [-] Removed Pro design tab

= 1.2.5 (20/10/2016) =
* Updated all the designs and fix the bug
* Fixed image display issue on mobile
* Replaced arrow images

= 1.2.4 =
* Updated slider js to latest version.
* Updated plugin design page.

= 1.2.3 =
* Fixed some css issues.

= 1.2.2 =
* Fixed some css issues.
* Resolved multiple slider jquery conflict issue.

= 1.2.1 =
* Fixed some bug
* Added Pro version with 16 designs

= 1.2 =
* Fixed some bug
* Added link to carousel mode

= 1.1 =
* Fixed some bug
* Added Limit

= 1.0 =
* Initial release.
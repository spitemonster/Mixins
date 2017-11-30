# Mixins

A collection of partials with mixins I use in practically every project. As of writing, 05/08/17 (5 August, not May 8), just a couple files and a handful of mixins and settings, but I intend on growing this repo as I work on more projects that require more and more tweaks.

_reset is vanilla CSS intended to replace normalize CSS in all my projects. There's a lot going on in Normalize.css that I don't use or don't know about, so I'd much rather build something from the ground up that I use to the fullest and understand thoroughly. As of now it just removes margin and padding from every element, eliminates text decoration from lists and sets the box sizing to border box, using prefixes from the...

_prefixer, a collection of mixins and extensions to take care of adding the necessary prefixes to every property. As of writing, contains mixins for transition, animation, linear gradient and box shadow and an extension for box-sizing. Proably won't go much farther, since everything is getting standardized now.

_fluidscale is my bullshit baby. ugly as sin compiled but VERY easy to set up a fluid typography that also incorporates typography scaling. just set your min and max font sizes and your scale and you're all set. right now it is set to scale between your two ideal sizes between 400px and 2560px. any smaller or bigger than that and the font will still scale but not as dramatically. for example, with your min and max set to 12px and 16px respectively, at 96px the base font size would be a little under 11.5px. at 5120px browser width the font would be 20px, which if you had a display that big you can just go to hell. additionally, this sets the line height of the various headings and paragraphs to 1.5x the font size for optimal viewing. as stated above, it is ugly as sin when compiled so if you're obsessed with your css being clean when it compiles down, this is not for you and you should maybe check out...

_fluidtype is kind of the progenitor of fluidscale. it's a really simple function/mixin combo that allows you to pick a min and max font-size and it sets the fluid size as well as a fluid line height.

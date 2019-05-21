---
layout:   post
title:    "Maker Challenge Day 11: PyPortal Stand"
# date:     2019-05-18 19:00:00 -0400
image:
    path: "https://source.unsplash.com/NL_DF0Klepc/800x300"
    thumbnail: "https://source.unsplash.com/NL_DF0Klepc/800x300"
    # overlay_filter: .5
    caption: "[Cesar Carlevarino Aragon at Unsplash](https://unsplash.com/photos/NL_DF0Klepc)"
tags: [challenge, maker, 100 day challenge]
---
Continuing my efforts to avoid making useless things just to fill up a slot in the challenge, I made a replacement for the case that came with my [PyPortal](https://www.adafruit.com/product/4116). The original got destroyed in an unfortunate incident involving high school freshmen and a concrete floor. The PyPortal itself is a a fairly small board running CircuitPython, with integrated sensors and an LCD screen. 

![pyportal in stand]({{"/assets/img/hundred-day-challenge/pyportal-stand.jpg"}})

I'm definitely going to be making an improved version of this one. My goal was to have an adjustable-angle stand for my PyPortal, but the geometry of the base and supports are off a bit. I reused the base assembly as the support, and it turned out to be much too long. Still, it works for now and will keep they PyPortal safer than not having a case of any sort.

To make the design, I started with [Adafruit's CAD repository](https://github.com/adafruit/Adafruit_CAD_Parts). I modeled up the pieces of the case based on the model of the board, and then added the hinges and support/base to make the stand self-supporting and relatively compact.  

Materials:

* 1/8" Baltic Birch from [Ocooch Hardwoods](https://ocoochhardwoods.com/plywood/baltic-birch-plywood/)
* Glue

<!-- Licensing info -->
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">PyPortal Stand</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Jackie Gerstein</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
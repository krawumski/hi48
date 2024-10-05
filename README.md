# HI48
When recently I got a new Xperia phone I could not find any HP calculator emulations that made use of the entire 21:9 display. The only options seemed to be letterboxing or expanding a smaller skin in the vertical direction none of which does the careful HP designs justice. This clearly was an unacceptable situation so on a rainy public holiday afternoon I started Photoshop and built a new skin for [Emu48](https://github.com/dgis/emu48android) from scratch. To enable the free placement of the rows of keys the graphics for each key and label were constructed as separate elements and then placed on a synthetic background (basically a coloured rectangle that can be scaled to any size). The resulting graphics are of a high fidelity without any compression artefacts.

The skin is inspired by Giuseppe Donnini's [Smart Charlemagne](https://www.hpmuseum.org/forum/thread-14197.html) set of skins and I borrowed his system for creating the KML scripts to support different versions of skins. There are currently skins for two different aspect ratios:

- 1:2.33, or 21:9. This is the somewhat unusual aspect ratio of Sony phones such as the Xperia 5. It represents the long shape of the HP48 rather well, especially since it does not have rounded corners. Could be a reasoon for HP nerds to get an Xperia.
- 1:2.0, or 18:9. After checking the usable aspect ratios of various phones I decided that this should work better on modern phones than a 16:9 aspect ratio. On phones with large corner radii such as the iPhone letterboxing cannot be avoided and from the numnbers I found the 2:1 aspect could work. Haven't checked it though!

## Colour Schemes
There are two different colour schemes for the keyboard, and two variants for the display ink. These are also inspired by Smart Charlemagne and I have adopted the naming. The following colour schemes are available:

## Keyboard
- Gold: Neutral grey background and a yellowish colour for the left shift functions reminiscent of the HP 11C.
- Charlie: Resembling the original HP48 with a slight red hue on the background and orange left-shift labels. Note that the keys are still neutral greyscale. This skin has a darker background and therefore a higher contrast.

## Display
- Coal: Greyscale LCD
- Blue: Light blue ink based on the screenshots in the June 1991 issue of the HP Journal, as explained by Giuseppe in his [post on the Museum of HP Calculators site](https://www.hpmuseum.org/forum/thread-14199.html).

I hope you find these useful. The 21:9 skin certainly looks great on my Xperia!

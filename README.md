# Vividity

**Vividity** is a brand new icon set for Ubuntu 18.04, featuring unified icons for most major applications. It is composed solely of SVG graphics, making it completely scalable for the best quality on all devices and screens.

## Why Vividity?

I started this icon set out of a desire to have a clean, unified, semi-flat icon set. For years, I was an avid fan of the Vibrancy and Revival icon themes -- even contributing icons to the former -- but neither of those were updated to the Ubuntu 18.04.

## Installation, Use, and Limitations

Right now, you'll need to manually download the repository, and copy or symlink the `Vividity` subdirectory into `/usr/share/icons`. The icon set is incomplete, so it uses Humanity and Breeze as its fallbacks.

Vividity is presently designed around a dark theme (Adapta-Nokto), although I'll add proper support for light themes later.

Icons sets don't work correctly with Snapcraft. Personally, I never use snaps, and this is one of the three reasons. I don't care to support them at this time.

You may need to tweak some `.desktop` files to search for the icon in the proper place, instead of the hardcoded location. I did this with IntelliJ and PyCharm.

## Plans and Timeline

The complete list of applications I plan to include icons for can be found on the wiki. I'm working on this on my own time, with no deadlines. However, I use Vividity on my main computer, meaning I'm looking at it for hours every day. That one factor will keep things moving forward.

I prioritize icons I regularly interact with, so those are likely to be done first. If you want to contribute icons for your favorite applications, you're welcome to!

## Issues and Icon Requests

Please open an issue for...

* Requesting icons,
* Reporting flaws in icons,
* Reporting wrong filenames or directory layouts,
* Any other mistakes.

Please *don't* use issues if you just don't like my designs. If you want to do it your way, please fork! :)

## Contributions

To make application icons, grab `Vividity/base.svg`, make a copy of it, and edit it in Inkscape. The `Foreground` layer contains a copy of the icon shape, to be used with `Set Clip` on the application artwork. The `Background` layer should be recolored with a gradient to match the icon's color scheme.

This is still, first and foremost, an icon set for my own use. As such, I may reject or modify your contribution if I don't like how they look; trust me when I say, it's not personal.

If you don't like the direction I'm going with the design, you're welcome to fork this project! I try to keep the repository clean and organized, so you can pull any of my changes into your fork as you like.

# Animated Digital Clock Timer

I created this plugin to make it easier to design mobile apps that rely on time-based interactions. 
For instance, you might need to display the time remaining in a game in minutes and seconds (eg. 13:37).
This plugin will create those numbers and mask a whole lot more that would otherwise be tedious to setup by hand.
With auto-animate transitions in place, your timer will then offer visually explicit countdowns between any 2 artboards.
It should look like flight departure times on those big mechanical time tables in the hallways of airports.


## How to use

1. Install the package.
2. In _Design_ mode, select a first  artboard, then shift-select a second one.
3. In the menus go to Plugins > Animated Digital Clock Timer.
4. Leave the defaults as they are to simply get an idea of the plugin's capabilities.
5. Click on "Create Timer Elements".
6. Switch to _Prototype_ mode.
7. Add a Tap-triggered, 5 seconds long _Ease-In-Out_, _auto-animate_ transition between the first artboard and the second one.
8. [Optional] Add a similar Tap-triggered, 5 seconds long _Ease-In-Out_, _auto-animate_ transition between the second artboard and the first one.
8. De-select all elements by clicking anywhere on the canvas.
9. Click on the Play icon in the top right to play the animation.

From there you can repeat that procedure between any 2 selected artboards, making changes to the font color, family and horizontal spacing.

## Good to know

1. To move your timer groups, simply shift-select them both in design mode and move them around.
2. XD does not have a Fonts API, so for now I decided to let users type the name of their font rather than trap them in a predefined list of common fonts.
3. The plugin modal dialog will remember the last values you used by storing them in a plugin-specific data file locally on your computer. If you ever run out of storage space that caching feature will silently fail and the dialog will always show the plugin defaults.
4. If you ever needed to rename the masked groups created by the plugin, make sure to give them the same name on both artboards, or auto-animate will fail.


## Contributing

Please use the [Issues](https://github.com/lelayf/AdobeXD-animated-digital-clock-timer/issues) page to report bugs, contribute fixes and make feature requests.



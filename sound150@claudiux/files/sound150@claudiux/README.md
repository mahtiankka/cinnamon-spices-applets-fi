# Enhanced Sound applet

 ▶︎ •၊၊||၊|။||||| 0:10 


## Summary

This *sound150@claudiux* applet is an enhancement of the Cinnamon system sound applet.

**This applet works with Pulseaudio or Pipewire.**

**It can display icons indicating that the microphone is muted or activated.**

**It avoids loud cracking sound at shutdown.**

**Sound volume:**

  * **The volume step can be redefined** (from 1% to 10%).
  * **All multiples of 25% (or only 100%) can be magnetized.**
  * Before Cinnamon 6.4, the **OSD** is compatible with the [Horizontal OSD](https://cinnamon-spices.linuxmint.com/extensions/view/93) Cinnamon extension.
  * The **OSD** is compatible with Cinnamon 6.4 (use of the 'Horizontal OSD' extension, or 'OSD with numbers' extension, is not recommended).
  * From Cinnamon 6.4, having a horizontal OSD requires the [OSD150@claudiux](https://cinnamon-spices.linuxmint.com/extensions/view/106) extension. Notifications are available to help you install and enable the OSD150@claudiux extension.

**The song's cover art** can be displayed when it is embedded in the file (.mp3, .flac ...) or available from the **[Radio3.0 applet](https://cinnamon-spices.linuxmint.com/applets/view/360)**.

**You can use the mouse wheel on this applet to control the sound volume. Use Ctrl+wheel or Shift+wheel to control the microphone volume.**

You can reverse this scrolling effect at will. (Only available from Cinnamon 6.4 and version 8.0.0 of this applet).

**The icon can be colored according to the volume when it exceeds 100%.**

From 0% to 100%: standard icon color.

From 101 to 115%: yellow icon (by default).

From 116 to 130%: orange icon (by default).

From 131 to 150%: red icon (by default).

*You can select other colors or choose not to display colors.*

**You can redefine multimedia key bindings.**

Successfully tested on Cinnamon versions 2.8 to 6.4 (Linux Mint 17.3 to 22.1). Does not work on Cinnamon prior to version 2.8 (Linux Mint prior to 17.3).

## Dependencies

This applet requires *playerctl*. If this package is not installed, the user can install it using the 'Install playerctl' option in the menu. If this option is absent from the menu, this means that *playerctrl* is already installed.

## Settings

 * Settings can be accessed by right-clicking on this applet icon (Configure... option of the context menu).

 * Since version 5.0.0, settings have been presented in a new way, with 4 tabs: *Behavior*, *Sound*, *Icon*, *Shortcuts*, making this applet highly configurable.

## FAQ

### Keyboard shortcuts are not respecting volume step

  1. Open the *Shortcuts* tab of this applet settings.
  2. Check the *Redefine Multimedia Keyboard Shortcuts* option.
  3. Click on the *Use the same shortcuts as those defined by Cinnamon* button.
  4. Close this settings window.
  5. If necessary, restart Cinnamon.

## Translations

The **Sound 150%** applet is designed to allow translation. A .pot template file is available, which you can use with software such as *poedit* to translate into your own language. You can then submit your translation on github, by forking [this repo](https://github.com/linuxmint/cinnamon-spices-applets) and making a pull request containing your changes.

Available translations are installed automatically when an update is performed.

**[Status of translations](https://github.com/linuxmint/cinnamon-spices-applets/blob/translation-status-tables/.translation-tables/tables/sound150%40claudiux.md#)**

Many thanks to all of the translators!

We welcome any new translations or updates.

## Contributors

Many thanks to [Rodrigo-Barros](https://github.com/Rodrigo-Barros) for his patch allowing to show the Spotify-player album art!

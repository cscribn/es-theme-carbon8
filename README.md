# Carbon8 Theme for EmulationStation

Have you ever had trouble discerning a system based on its logo or controller? Have you wondered whether `Game Gear` should be sorted with the `Gs`, for `Game`, or the `Ss`, for `Sega`? This theme was designed to address those issues. Instead of displaying the system's controller, it instead displays the full system name, based on the [Libretro Database](https://db.libretro.com). Minimal meta data is utilized.

![System Select](README/System%20Select.png) ![Detailed Game List](README/Detailed%20Game%20List.png)

Based on ['carbon' v2.4 - 08-16-2016 by Rookervik](https://github.com/RetroPie/es-theme-carbon).

## Why "8"?

Eight is the number of bits in a character. For systems, Carbon8 uses characters instead of controller images.

## Configuration

### Change Font

Copy your font to /etc/emulationstation/themes/carbon/art folder. Rename the original font "Cabin-Bold.ttf" to "Cabin-Bold.ttf.backup" and then rename your font to "Cabin-Bold.ttf".

### Change Color

To change the colors open carbon.xml with a text editor. Find all occurances of "8b0000" and replace them with your chosen color.

### Change Sound

To change the sound effect, replace /art/scroll.wav with what ever WAV file you would like.

# Carbon8 Theme for EmulationStation

Carbon8 is an EmulationStation version 4 compatible theme, making it ideal for low-powered systems using RetroPie or ArkOS, as well as the PlayStation Classic. It displays the system's fullname from your `es_settings.cfg`. It displays mini-consoles instead of controller overlays. Only "Released", "Developer", and "Publisher" meta data is utilized.

![System Select](art/README/System%20Select.png) ![Detailed Game List](art/README/Detailed%20Game%20List.png)

Based on ['carbon' v2.4 - 08-16-2016 by Rookervik](https://github.com/RetroPie/es-theme-carbon).

## Why "8"?

Eight is the number of bits in a character. For systems, Carbon8 uses characters instead of controller images.

## Configuration

### Change Font

Copy your font to /etc/emulationstation/themes/carbon8/art folder. For the gamelist text, rename the original font "Cabin-Bold.ttf" to "Cabin-Bold.ttf.bak" and then rename your font to "Cabin-Bold.ttf". For the system text, rename the original font "Akrobat-Bold.otf" to "Akrobat-Bold.otf.bak" and then rename your font to "Akrobat-Bold.otf".

### Change Color

To change the colors open colors.xml with a text editor. Find all occurances of "8b0000" and replace them with your chosen color.

### Change Sound

To change the sound effect, replace /art/scroll.wav with what ever WAV file you would like.

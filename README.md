# EasyEffects presets for Surface devices built in speakers

This is a preset for the [EasyEffects](https://github.com/wwmm/easyeffects) sound effect Linux app that I tuned to get better quality audio out of my Surface Laptop (3)'s built in speakers.

It will probably sound fine with a few tweaks on other Surface devices, depending on how their frequency response is.

## Installation

1. Install EasyEffects (I use the flatpak version)
2. Copy the preset `.json` file to the EasyEffects presets folder: `~/.var/app/com.github.wwmm.easyeffects/config/easyeffects/output/` (for the flatpak version)
3. Open EasyEffects and load the preset from the 'Presets' menu
4. To have the preset automatically activate when the speakers is selected:
    * Go to the 'PipeWire' tab -> 'Presets Autoloading'
    * Leave the first field to the default 'Built-in Analog Audio Stereo'
    * Select your preset in the 2nd field
    * Click the `+` button

Note: You will have to repeat steps 2 -> 4 for a 'Blank' preset while having headphones connected so that effects don't get applied to headphone outputs.

## Customizing

I suggest adjusting the EQ to your liking in a -5 dB to +5 dB range on each frequency band, don't go too hard or else the audio will clip and sound bad.

## Tuning

Adjust the Bass Enhancer's frequency to see which gives you the cleanest or loudest sound. Don't go too low, as the small speakers can't reproduce too low frequencies and it will also drag the rest of the audio down.

In Stereo Tools, go to the Stereo Matrix tab and adjust the Side Level to boost the stereo separation.

You can also play around with the Filter's frequency, but I suggest you keep it at at least 80 Hz. This is important as the small speakers can't reproduce frequencies this low at audible volumes and sparing them from some work makes the rest of the audio frequencies sound cleaner.


# SmartColourHackathon

## chroma-key.js 

A simple Javascript program whch allows users to replace a chroma range to a different chroma range. The program is based on the chroma-key.js written by Dave Raggett (<dsr@w3.org>). And improved by Duke Wu with chroma range/colour replacement feature added.

### Usage

**Attributes in HTML img tag:**
sample code: chroma-key-demo.html

  * ckey-r - Chroma range red value
  * ckey-g - Chroma range green value
  * ckey-b - Chroma rance blue value
  * data-rr - Replacement red value
  * data-rg - Replacement green value
  * data-rb - Replacement blue value
  * data-delta - Width of the chroma range
  * adv - Advanced features:
    1. 1 - Replaced by a chroma range
    2. 2 - Remove the chroma range
    3. 3 - Replaced by the given colour)


## colour_space_conv.js 

A simple Javascript program which converts colour spaces between RGB and LAB. Based on the codes on https://github.com/antimatter15/rgb-lab.

### Usage

**Functions**
  * lab2rgb: converts from LAB to RGB
  * rgb2lab: converts from RGB to LAB
  * deltaE: calculate the perceptual distance between colors in CIELAB

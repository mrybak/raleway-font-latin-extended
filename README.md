# Latin extended for Raleway font

## Motivation

**Raleway** font is available in [Google fonts](https://www.google.com/fonts#QuickUsePlace:quickUse/Family:Raleway), but unfortunately it lacks latin-ext characters, which makes it unusable for some people.

## What is included

CSS included in this repo fixes the problem for **Polish** characters.
Download repo and check out the example to see how it works.  

Also, there is `generator_config.txt` file that contains configuration for FontSquirrel. See details below.


## How to customize

If you characters other than Polish, do the following:

1. [Download the Raleway font](http://www.impallari.com/projects/update/100)  
2. Go to [FontSquirrel](http://www.fontsquirrel.com/tools/webfont-generator) 
3. In 'Add Fonts' box upload all `.ttf` files from downloaded package and `generator_config.txt` from this repo 
4. Select desired character subset and generate your kit
5. Open `fonts.css` file from your downloaded kit   
6. For each font that you need (for example, 'ralewaysemibold' if you need *Raleway Semi Bold*):
    1. Copy the `src` attribute value of this font
    2. Find the corresponding font in original `fonts.css` file from repo (there are comments relating each font-weight to original font name)
    3. Overwrite the `src` attribute value

###### If you have any questions, please feel free to ask.



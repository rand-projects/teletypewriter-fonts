# Teletypewriter-fonts

**Teletypewriter-fonts** is a collection of TrueType fonts (`.ttf`) for Model-28 (BAUDOT) and Model-35 (ASCII) typeboxes based on photographs of actual typeboxes. The glyphs are then arranged into sets whose two-letter abbreviations would have been stamped on the typebox.

The purpose is to archive the fonts for historical purposes. These fonts are useful for such things displaying historical aviation weather data, old stock reports, and when using retro computer simulators.

All fonts are licensed with the [SIL Open Font License (OFL)](https://scripts.sil.org/OFL).

The photographs used to develop the fonts can be found in the `photos` directory.

The fonts are broken up into Model-28 fonts and Model-35 fonts. Each font
has a two letter description that denotes what glyphs appear in the
typebox. Lists of these two letter abbreviation can be found in:

* http://www.bitsavers.org/communications/teletype/35/1201B_Mod35_Parts_Dec75.pdf.
Model-35 typebox (also called `pallets` in the manuals) information is on page 43.

* http://www.bitsavers.org/communications/teletype/28/1149B_Mod28_Parts_Apr63.pdf.
Model-28 typebox information on pages 3-42 to 3-44.

* https://www.navy-radio.com/manuals/tty/typebox-code.pdf.
More expansive list of Model-28 typebox codes. This isn't the last typebox list, there are many more typeboxes that were developed, but I don't have any more sources after this one.

* https://www.navy-radio.com/manuals-ttycorp.htm.
Best source for Teletype information.  

Each font has digits and letters, as well as the '`-`' character in the
usual place. If a typebox has a normal printing character found on the keyboard, it will appear in its usual place. Lowercase characters are mapped to the uppercase ones. Other glyphs are placed at random places.
These places are found by looking at the `.png` file accompanying each font.

## Specific Font Notes

### 28RD and 28RE

These fonts were used for aviation weather reports. The normal aviation typebox was 'RD'. The only difference between 'RD' and 'RE' is that the zero is
slashed in 'RE'. There were sky cover glyphs for clear, scattered, broken, and overcast. I added one for 'few'. It is the scattered glyph, but the line in the middle isn't continuous. 'Few' is a relatively new term used starting when METARs were introduced. For historical accuracy, use the scattered glyph instead of the one for 'few'.

### 28RA

This was the normal press teletype font.

### 28RB

Commonly used for stock reporting. Back in the day (before 1997), stocks were only reported in 1/8th of a dollar increments.

### 35TD, 35TD1, 35TD2, and 35TD3

The 35TD typebox was the usual typebox that came with the stock Model-35. It has the unusual feature that the letter '`O`' has a slash in it, and not the number '`0`' (these days, if something that looks like '`0`' has a slash in it, it is a zero-- but back in the day it wasn't really standardized). All of the Model-35's I ever used were like this. For those who want a slashed-zero, use 35TD1. If you don't want any slashes, use 35TD2. Which glyphs are in a typebox is supposed to be standardized, but it actually isn't. There are TD typeboxes that have alternate glyphs (straight from the factory), which are still marked TD.
35TD3 is an example of one of these. The quotes are different, the underscore is a back arrow, and the caret is an up-arrow.

If you want to use 35TD, but also want to be able to tell lower from uppercase, there is `35TDlc`. In this font the lowercase letters are the same as uppercase letters, but shrunk by 20%.

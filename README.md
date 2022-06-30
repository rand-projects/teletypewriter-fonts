# Teletypewriter-fonts

**Teletypewriter-fonts** is a collection of TrueType fonts (`.ttf`) for Model-28 (BAUDOT), Model-35 (ASCII), and Model-37 (ASCII) typeboxes based on photographs of actual typeboxes or other sources. The glyphs are then arranged into sets whose two-letter abbreviations would have been stamped on the typebox.

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

### 35TD, 35DC

The 35TD and the 35DC were common Model-35 typeboxes. The 35DC is the one I have seen used the most (although I have seen a bunch of typeboxes marked `TD` containing the `DC` glyph set with the famous slashed letter
'O'). The difference is that the 35TD uses the up arrow for the caret and the back arrow for underscore (backspace). The 35DC uses the normal caret glyph and uses a regular underscore. Again, there are lots of variants of these in the wild. My glyphs are based on the manuals. You may notice the use of slash through the letter 'O' in some fonts-- this is not an error.

Both 35TD and 35DC have lowercase versions, where there are 80% size characters for lowercase. This is useful for using the font when you have access to lowercase terminals. Actual fonts were uppercase only.

### 37ts109

The Model-37 was an upper and lower case typebox teletype. There were different fonts-- `ts109` stands for type style 109 and was one of the available fonts. This font was generated using a sample from the Model-37 brochure and YouTube videos. A non-slash zero and an alternative digit `1` form are found in the `copyright` and `underscore a` positions. It seems the brochure example used the lower case `l` character for both lower case `l` and `1`. Other samples show a different style `1`, and that is the one included in the main font.
# Teletypewriter-fonts

**Teletypewriter-fonts** is a collection of TrueType fonts (`.ttf`) for various historic printers and teletypes.

The purpose is to archive the fonts for historical purposes. These fonts are useful for such things displaying historical aviation weather data, old stock reports, and when using retro computer simulators.

All fonts are licensed with the [SIL Open Font License (OFL)](https://scripts.sil.org/OFL).

The photographs used to develop some of the fonts can be found in the `photos` subdirectory associated with its fonts.

Fonts are usually marked either `-Light` or `-Book`. Light fonts come from original pictures-- before the glyph hit ink and paper. These are
usually thinner than desired. Book fonts are more what you would see after the glyph was rendered on paper. For emulating terminals and the 
such, book fonts are recommended.

Fonts that have the letters `lc` in the name denote that this font only
has uppercase letters normally, but that lowercase letters that are 80% the size the of uppercase letter is provided. This is useful if you are using the font for a modern system.

Each font has an associated `.png` file where the font can be viewed.

## Subdirectories

### **tty**

Divided up into the `ts101` and `ts109` subdirectories.

#### **tty/ts101**

`ts101`, also known as 'Murray' fonts, contains Model-28, Model-35, and Model-33 fonts.
Model-28 and Model-35 fonts consisted of individual 'pallets' put inside a 'typebox'. Model-33 fonts were punched as a unit on a type wheel.

All of these fonts contain a two letter designation. For Model-28
and Model-35 fonts, these letters
denote what glyphs (called 'pallets') appear in the
typebox. Lists of these two letter abbreviation can be found in:

* http://www.bitsavers.org/communications/teletype/35/1201B_Mod35_Parts_Dec75.pdf.
Model-35 typebox information is on page 43.

* http://www.bitsavers.org/communications/teletype/28/1149B_Mod28_Parts_Apr63.pdf.
Model-28 typebox information on pages 3-42 to 3-44.

* https://www.telecomarchive.com/docs/bsp-archive/573/573-115-800_I2.pdf.
More expansive list of Model-28 typebox codes. Found on pages 53-57.

* https://www.navy-radio.com/manuals-ttycorp.htm.
Best source for Teletype information.  

Each font has digits and letters, as well as the '`-`' character in the
usual place. If a typebox has a normal printing character found on the keyboard, it will appear in its usual place. Lowercase characters are sometimes mapped to the uppercase ones. For Model-28 fonts, special characters are placed in the lowercase letter where it normally would have been associated with an uppercase letter, but in the 'figs' position.

There are many typebox codes that can be created from the glyphs in
`TTY2835ts101-Light/Book.ttf`. See the `README.txt` file for details.

Some of the more common ones are provided as `Book` fonts:

* **TTY28RD and TTY28RE**:  These fonts were used for aviation weather reports. The normal aviation typebox was 'RD'. The only difference between 'RD' and 'RE' is that the zero is
slashed in 'RE'. There were sky cover glyphs for clear, scattered, broken, and overcast. I added one for 'few'. It is the scattered glyph, but the line in the middle isn't continuous. 'Few' is a relatively new term used starting when METARs were introduced. For historical accuracy, use the scattered glyph instead of the one for 'few'.

* **TTY28RA**: This was the normal 'text' teletype font.

* **TTY28RB**: Commonly used for stock reporting. Back in the day (before 1997), stocks were only reported in 1/8th of a dollar increments.

* **TTY35TD and TTY35DC**: The 35TD and the 35DC were common Model-35 typeboxes. The 35DC is the one I have seen used the most (although I have seen a bunch of typeboxes marked `TD` containing the `DC` glyph set with the famous slashed letter
'O'). The main difference is that the 35TD uses the up arrow for the caret and the back arrow for underscore. A fancier comma and double quote character are found in the 35DC, along with a normal caret glyph and underscore. Again, there are lots of variants of these in the wild. My glyphs are based on the manuals. Both 35TD and 35DC have lowercase versions, where there are 80% size characters for lowercase. This is useful for using the font when you have access to lowercase terminals. Actual fonts were uppercase only.

#### **tty/ts109**

This type style includes the Model-37 'ts109' typebox.

The Model-37 was an upper and lower case typebox teletype. There were different fonts-- `ts109` stands for type style 109 and was one of the available fonts. This font was generated using a sample from the Model-37 brochure and YouTube videos. A non-slash zero and an alternative digit `1` form are found in the `copyright` and `underscore a` positions. It seems the brochure example used the lower case `l` character for both lower case `l` and `1`. Other samples show a different style `1`, and that is the one included in the main font.

### **ti**

Fonts for Texas Instruments Silent-700 printers.

### **dec**

Fonts for Digital printers, such as the LA-36 (Decwriter ii).

### **misc**

Various files, mostly notes to myself.

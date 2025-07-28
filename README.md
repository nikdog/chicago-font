# chicago-font
## History
Chicago is a sans-serif typeface designed by Susan Kare for Apple Computer. It was used in the Macintosh operating system user interface between 1984 and 1997 and was an important part of Apple's brand identity. It was also used in early versions of the iPod user interface. Chicago was initially a bitmap font; as the Apple OS’s capabilities improved, Apple commissioned the type foundry Bigelow & Holmes to create a vector-based TrueType version. The typeface is named after the U.S. city of Chicago, following the theme of original Macintosh fonts being named after major world cities.
## About
This Repo merges the Latin-US, Latin-ISO, Greek, & Cyrillic versions.
### Files
Chicago v0.5.5.ttf - TTF is for TrueType Font.

TrueType is an outline font standard developed by Apple in the late 1980s as a competitor to Adobe's Type 1 fonts. Microsoft also adopted it, making it a standard for both Mac OS and Windows.

Chicago_15.bdf - BDF stands for Glyph Bitmap Distribution Format.

This is a human-readable text file format developed by Adobe for storing bitmap fonts.

BDF fonts were a standard for the X Window System (the graphical environment on Linux) and are still used today, often as a source format for creating other types of bitmap fonts.

You could open this file in a text editor and see the font's metadata and the raw pixel data for each character.

Chicago_15.pf2 - PF2 is a PFF2 (PUPA Font Format) font.

This is a bitmap font format specifically designed for the GRUB 2 bootloader.

Because GRUB operates in a pre-OS environment, it needs its own self-contained font format. PF2 is a simple, compact, and Unicode-aware format for this purpose.

You would use this font to change the font of the GRUB menu when you boot your system.

Chicago_15.psf - PSF stands for PC Screen Font.

This is a bitmap font format used by the Linux kernel for the virtual console (TTY).

The virtual console is the text-based interface you see before a graphical environment loads, or when you switch to it with Ctrl+Alt+F1 through F6.

PSF fonts are very basic, fixed-width fonts that were originally used on MS-DOS and have been adapted for Linux. They usually only contain up to 256 or 512 glyphs.

Chicago_15.psfu.gz - PSFU is an extension of the PSF format, where the 'u' indicates that it includes a Unicode mapping table.

This is a crucial addition that allows the font to support a much wider range of characters beyond the basic ASCII set.

The .gz extension means the file has been compressed using gzip to save space. This is a common practice for console fonts, which are often stored in /usr/share/consolefonts.

## Detailed History
Susan Kare said that Chicago was the first font to be developed for the Macintosh. Before the team settled on the convention of naming fonts after "world cities", it was called Elefont (Elefont is also the name of a bold semi-serif typeface designed by Bob McGrath in 1978). The first bitmap version included only a 12 pt. version. This font, with only very minor changes to spacing, was used for menus, dialogs, window titles, and text labels, through version 7.6 of the system. The TrueType version had many differences from the bitmap version, which became more apparent at greater sizes. One of Chicago's features was that it could remain legible while being made "grey" (to indicate a disabled menu item) by the removal of every other pixel (since actual grey type was not supported by the original Macintosh graphics hardware). The zero was slashed to distinguish it from capital "O".

In Mac OS 8, Charcoal replaced Chicago as the default system font. Chicago continued to be distributed as a standard component of the system, and Apple even urged developers to keep designing user interfaces for the Chicago typeface, since the new alternate fonts used the Chicago metrics as a foundation.

German-language versions of the Mac OS, as well as all language versions of Mac OS 9, had a different rendering of the 12-point version of Chicago. The letter W had two dips instead of one at the bottom of the letter, the letter V had its lower tip at the centre instead of veering left, and the letter I (capital "i") had serifs at the top and bottom, distinguishing it from l (lowercase "L"). A mix of this and the original Chicago was used in the original iPod.

Chicago was also used in Apple marketing materials. It was common to find this font in early amateur desktop publishing productions, since it was available as part of the system. While Apple gravitated away from Chicago following the adoption of the relatively easier-to-read Charcoal as part of the platinum theme in Mac OS, it was later revived in the user interface for the iPod music player, where legibility on its low resolution two-color screen once again became an asset. With the introduction of the iPod mini, a smaller typeface was needed, and the Espy Sans font from the Apple Newton was used. Finally, with the introduction of the iPod Photo, the color iPod interface changed to Podium Sans—a bitmap font similar to the Myriad Pro typeface which Apple has adopted gradually for its marketing since 2002.

The Chicago pixel typeface was also adapted by Squaresoft for use in the English releases of their Super NES titles, such as Final Fantasy VI and Chrono Trigger.

Though the original font is no longer bundled with macOS, two Thai-language fonts bundled with macOS, Krungthep and Silom, use Chicago for their Latin letters and hence can be used as modern replacements.

Chicago is a registered trademark ("typeface fonts recorded on computer software"), belonging to Apple since August 1996 (U.S. Trademark 74,556,614).

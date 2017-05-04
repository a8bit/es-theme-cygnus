## EmulationStation Theme: Cygnus
Cygnus is a clean theme that displays both large preview images, videos, marquees,  all title-oriented metadata and some useful user-oriented metadata.

### Variant: Cygnus NoMeta
The NoMeta variant omits all of the metadata, extending the game list to the height of the screen.

### Variant: Cygnus SimpleArt
The SimpleArt variant hides the overlayed boxart and marquee images on the video display, it removes the static video if no video exists and instead shows the boxart in large format, the video still displays if it exists.

### Variant: Cygnus SimpleArt NoMeta
The SimpleArt-NoMeta variant combines both of the previous variants for a far more minimal look.

### Preview Image Size
Since Cygnus uses bigger preview images than normal, you may wish to set your scraper to pull larger image files.  If you are using sselph's scraper, you can use the -max_width parameter to do this, matching the width of each system's layout. A size of 800x800 should be large enough to look good all the way up to 1080p

### Advanced Feature: Color Sets 
Cygnus comes with 3 different color sets, allowing you to easily change the look of the theme.  The Cygnus color set is used by default.  To use a different color set, edit Cygnus/cygnus.xml, and point the <include> tag at any of the xml files in Cygnus/_res/colorsets/.

For example, to use the monolight color set, change:
<include>`./_res/colorsets/cygnus.xml`</include>    
	to    
<include>`./_res/colorsets/terminal.xml`</include> 	This will give your Cygnus a green tint.   
	or    
<include>`./_res/colorsets/mono.xml`</include> 	This will make your Cygnus monochrome.    

Creating new color sets is really simple, as there is only one file to edit.  Just make a copy of an existing colorset xml file, rename it, and edit away.  That one file is all you need.

Some system logos may look bad with certain color sets.  Better support for the .svg stroke property in EmulationStation would help but, until that happens, there's not much to do about this other than to change the logo or the color set.

### Credits
All xml, and some images created by Steve Boswell (ChoccyHobNob).

Based on the "Eudora" theme by AmadhiX, which is in turn based on the "Carbon" theme by Eric Hettervik, which is in turn based on "Simple" by Nils Bonenberger.  Most system logos and line art images are borrowed from these themes.

The following fonts are used under the licenses included with the font files:
"Titillium Web", "Adobe Blank" 

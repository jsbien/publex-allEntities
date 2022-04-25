# TCDH Entities

This repo contains the allEntities file developed at the Trier Center for Digital Humanities with numerous special characters for display on the web.
In particular, this can be used in the Publex tool for the display of dictionaries and the special characters they contain.
With the help of the KomplettFont file, the characters can be viewed in the Glyphr Studio web tool.

## How to use the allEntities file

1. Search for desired character in the allEntities file:

For this, you can explore the KompLett font in the GlyphrStudio web tool. Load the file KompLettR.ttf into Glyphr Studio (www.glyphrstudio.com/online) and make sure you choose to import all glyphs. Choose your character in the Private Use Area of the font.


2. Get the position of your character (hexadecimal code).

3. Look up the character's name in the allEntities.xml.

4. In the XML file of your dictionary text, replace the corresponding special character with "&" + entity name +";" (e.g. “&plusaboveu;”).

5. To display the special character, it has to be used together with the KompLettFont.

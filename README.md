# untouched_nature
Untouched Nature is a complex mod that adds new worldgen features, biomes, trees and plants, new magical mechanics and stuff, plenty of decorations and advanced cooking.

Currently UN is available in English and Russian languages.If you want to translate it to your language (and you know flora well and you are ready for tons of things to translate...), pm me on the CurseForge page or here in the issues section. Here in the repository you can find all the files you need:

* en_us.lang (all basic stuff goes there)
* ru_ru.lang (if you feel more comfortable to translate from russian)

You would need to make a renamed to your language copy of the .lang file with your translated names after the "something.goes_here.block_name=" instead of the original names.Use any Notepad++ like tool.

PATCHOULI BOOKS

UN uses Patchouli for its guidebooks, so you can translate them too.It has less stuff and so it is much easier to do.Use any Notepad++ like tool to open json files and translate normal text like "Untouched Nature" in here:
{
  "name": "books.patchouli.lisfestyle.name",
  "subtitle": "Untouched Nature",
  "landing_text": "books.patchouli.lifestyle",
  "model": "untouched_nature:book_green",
  "book_texture": "patchouli:textures/gui/book_green.png",
  "version": "0",
  "creative_tab": "tabuntouchednature",
  "show_progress": false,
  "pause_game": true
}

or "Cotton", "Cotton bush", "Cotton bush is a high plant, native to warm and hot plains-like biomes.Cotton bush gives cotton fiber when right-clicked, and drop cotton seeds when destroyed.Cotton can be cultivated as a crop, using these seeds." in here:

{
  "name": "Cotton",
  "category": "cloth",
  "icon": "untouched_nature:textures/items/cotton_fiber.png",
  "sortnum": 3,
  "pages": [
  {
	  "type": "spotlight",
      "item": "untouched_nature:unbushcotton",
      "title": "Cotton bush",
      "text": "Cotton bush is a high plant, native to warm and hot plains-like biomes.Cotton bush gives cotton fiber when right-clicked, and drop cotton seeds when destroyed.Cotton can be cultivated as a crop, using these seeds."
      
Look into Patchouli wiki page if you need more info. Be sure to create a folder with right language name for your book translations, like en_us.

Have fun! ;-)


	
   	

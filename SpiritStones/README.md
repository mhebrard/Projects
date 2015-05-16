This graph shows all the cards from the game Spirit Stones. Cards are linked according to their **"evolution path"**.

[Edit] Cards are grouped by class, and stratified by number of star.

###Functions
Color of circles refers to class: red = Warrior, purple = Mage, green = Archer, yellow = Thief.

When you click on a circle:

* Cards needed to create the current one (ascendants) were emphasized and links are dashed.
* Cards obtained from the current one (descendants) were emphasized and links are bolded.
* Card's image and information are displayed in the sidebox.

The list of cards, sorted by name, is present in the sidebox.  
When you select a card from the list:

* its information is displayed 
* the graph emphasized its path.

###Technics
Data are store in a spreadsheet in google drive.  
There are imported and displayed using D3.js library,   
using a force-directed graph.

###Thanks
* Thanks to [SpiritStone](https://play.google.com/store/apps/details?id=com.gamevil.spiritstones.global.free) for the game and all the  related data.
* Thanks to [thommo](http://m.gamevilusa.com/forums/member.php?151495-thommo) for shares the cards' information.
* Thanks to [this site](http://www.spiritstones.info/) ~~to share the images~~. (cross-reference problem)
* Thanks to [D3.js](http://d3js.org/) for the [force layout](http://bl.ocks.org/mbostock/4062045).

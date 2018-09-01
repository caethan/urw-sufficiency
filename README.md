# Caethan's UnReal World self-sufficiency mod

This is a set of modifications for the freeware roguelike game [UnReal World](http://www.unrealworld.fi/) developed by Sami Maaranen and Erkka Lehmus.

Last updated with UnReal World 3.51.

This mod allows you to live more self-sufficiently, crafting most needed tools and items with some effort on your own without trading.
Not everything is available --- complex armor and weapons will still have to be found elsewhere, but simple birchbark crafting, smithing, and weaving, along with some other small crafts and cooking, can now be done on your own.

Also includes some updates to the in-game encyclopedia with information about some of the new items, as well as tile graphics for them.

Enjoy!

# Installation Instructions

The first step to installing the mod is to find where Unreal World is installed on your computer.
If you've installed it manually from the developer's website, just remember where you put it.
If you're running it from Steam:
* Open up the game properties by right-clicking on the game from the Steam interface and selecting "Properties".
* Switch to the "Local Files" tab.
* Click on "Browse Local Files".  This will open up a window in Finder (for Macs) or Explorer (for Windows) at the root of the installation.
* For Macs:
    - There will be an icon with the label "UrW.app".  Right-click on it and select "Show Package Contents". This will open up another folder.
    - Open the "Contents" folder, then the "Resources" folder.
    - This final Resources folder is where mod files should go.
* For Windows:
    - TBD
* Copy over all the *.txt files in the mod download to the Unreal World folder.  Some of them will copy over the original files provided with the game.
You may want to make a backup of the original files to remove the mod in the future.
* Copy over the GAME.NFO file.  This updates the encyclopedia with the new modded items.
* There are two subfolders in both the Unreal World folder and the mod folder:
    - "truegfx":  pictures used in the encyclopedia and for various other purposes
    - "truetile": sprites for items and creatures in the game
* Copy over the contents of each of these folders in the mod into the Unreal World folders.
You shouldn't be copying over any existing files here.
* Start up the game and enjoy the new options!

# Changes from vanilla

## Updates to Current Items

* Slender trunks replaced with staffs for several recipes.  This allows staff quality to affect the final item quality, enabling you to build high quality items with some effort.
	- Grainflail
	- Ski stick
	- Sesta
* [noquality] added for some ingredients of fixed quality to avoid negatively impacting finished quality:
	- Wooden cup and bowl: block of wood
		- skill adjustment changed from +20% to -20% to compensate
	- Wooden shovel: block of wood
		- skill adjustment changed from +10% to -30% to compensate
	- Wooden stake and staff: Slender trunk
		- skill adjustment reduced by 40% each to compensate

## New Buildings

* Well added
    - Dig for water nearby your settlement
* Road added
    - Organize your settlement with roads


## New Crafts

* Craft items from birch bark
    - Peel birch bark from nearby birch trees
    - Necklace
    - Cap
    - Shoes
    - Box
    - Basket
    - Birch-bark canoe!
* Make low quality cords from soaked branches
* Make your own sauna scoop
* Craft nets, fishing poles, and wooden tubs and barrels

## Cooking

* Render fat to tallow
* Make hard biscuits
* Roast vegetables in the fire
* Dry berries and mushrooms

## Flora

* New cultivated flax plant with nutritious seeds
* Cultivated plants can be occasionally found in the wild
* Fixed bug making lake reed too abundant

## Ironworking

* Gather raw ore from mires
* Bury firewood and burn it to make charcoal for smithing
* Quarry a stone anvil and whetstone
* Build a bloomery furnace and smelt the raw ore into blooms
* Build a forge and hammer the blooms into wrought iron
* Hammer the wrought iron into useful tools:
    - Axes
    - Spears
    - Knives
    - Shovel
    - Sickle
    - Pot
    - Fish hooks

## Spinning and Weaving

* Gather (unthreshed) nettles, hemp, or flax (more productive)
* Soak the unthreshed stalks in water for a few weeks to rot away everything but the fibres.
* Dry the retted plants.
* Comb out the fibre from the dried and retted stalks.
* Spin the extracted fibre into yarn.
* Weave the yarn into cloth.
* Use the yarn and cloth to make homepsun items!
    - Clothes
    - Cords and rope
    - Bags
    - Quilt clothing with gathered feathers for extra warmth!


# Sources, Credit, and Inspiration

Many thanks to:
* The original developers Sami Maaranen and Erkka Lehmus for creating URW and its modding system in the first place.
* Many mod authors whose original work inspired this mod's development:
	* Rain for his Ironworking and Cloth mods which were used as the original base for the weaving and smithing sections
		* Ironworking - http://z3.invisionfree.com/UrW_forum/index.php?showtopic=2147
		* Cloth - http://z3.invisionfree.com/UrW_forum/index.php?showtopic=1839&st=0
	* Buoidda
		* http://z3.invisionfree.com/UrW_forum/index.php?showtopic=8043
	* Endive
		* http://z3.invisionfree.com/UrW_forum/index.php?showtopic=3071
	* Lasse & Weathereye
		* http://z3.invisionfree.com/UrW_forum/index.php?showtopic=5331
	* Brygun
		* http://z3.invisionfree.com/UrW_forum/index.php?showtopic=3818&st=0#entry22022885
    * thefinn
        * http://z3.invisionfree.com/UrW_forum/index.php?showtopic=8082
* The artists who drew the sprites
	* Kaaven (many various sprites)
		* http://z3.invisionfree.com/UrW_forum/index.php?showtopic=7331&st=0
    * thefinn (barrel sprites)
* The photographers who provided the pictures for the encyclopedia
    * Birch-bark cap - Fanny Schertzer, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=10890204
		
## Changelist

#### 1.1

Minor changes to maintain compatibility with URW 3.5.

#### 1.0

Initial completed release, including spinning and weaving.

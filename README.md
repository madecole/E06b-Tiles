# E06b-Tiles
Playing with the Tiled Map Editor

This is an opportunity for you to experiment with using the Tiled Map Editor to build a 2D platformer.

 * Download the Tiled Map Editor at [https://www.mapeditor.org](https://www.mapeditor.org). Follow the links to "Download at itch.io", click the "Download Now" button. Feel free to donate, or click the "No thanks, just take me to the downloads" link. Then download the version appropriate for your computer. *If you are using a computer in the lap, make sure you download "Tiled for Windows (64-bit), snapshot"*
 * In this repository, you will find a map.tmx file. This is set up with some initial tiles (in the assets folder) for you to create an orthogonal map. Open map.tmx in Tiled.
 * map.tmx has two layers, Platforms and Coins. Anything you draw in Platforms will be an object to stand on or an obstacle; anything you draw in Coins will be a source of points.
 * Use the stamp brush to add tiles from the Terrain Tool to your map. When you are happy with the layout, save the file.
 * open and run main1.py. You should see a character that you can move and cause to jump in the map you have drawn; you should be able to use the character to collect coins.
 * repeat until you are happy with your platformer level. If you wish to change the dimensions of the map, select the Map->Map Properties menu item and adjust the width and height of the file.

To earn extra credit,

 * Create main2.py
 * Copy into main2.py the code found here: [http://arcade.academy/examples/09_endgame.html#endgame](http://arcade.academy/examples/09_endgame.html#endgame).
 * in main2.py, delete the references to sounds (lines 72–75, 184, 213–214, 230, 244)
 * Create three new maps, called map2_level_1.tmx, map2_level_2.tmx, and map2_level_3.tmx
 * In each of those three maps, you will the following layers: Platforms, Coins, Foreground, Background, Don't Touch
 * Find, create, or download assets to fill out this three-level platformer. 
 * Make changes until you have a working three-level game

As always, update the LICENSE, this file (README.md) and submit the URL to your repository on Canvas.


This program explores the capabilites of the Tiled application. A 2D platformer level is created and tested with a movable sprite that can collect coins and jump between platforms. 

## Mac OS X bundle for Dwarf Fortress

![Dock screenshot](/screenshots/dock.png)

The current Mac version of this awesome game is not a single application bundle, but like the
Windows version it consists of a directory containing the application along with data files.

This project provides a way to "wrap" the game into application bundle so you can put the whole thing
into your `Applications` folder, enjoy pretty icon in your Dock and absence of ugly console window.

# Installation

1. Download the Mac version of Dwarf Fortress: http://www.bay12games.com/dwarves/
2. Download the bundle: https://github.com/vbo/df_osx_bundle/archive/master.zip
3. Put the game files directly into Dwarf Fortress.app/Contents/MacOS directory (from Finder you can right-click on Dwarf Fortress.app and choose `Show Package Contents`)
4. Put Dwarf Fortress.app wherever you like and open it (e.g. using double-click from Finder)
5. Strike The Earth!

# Retina issues

Dwarf Fortress has some known bugs related to retina support (e.g. http://www.bay12games.com/dwarves/mantisbt/view.php?id=6031).
Some of them actually solved by application bundle itself (that marks Dwarf Fortress as high-resolution uncapable so it looks pixelated even on retina).
If you want to play fullscreen though or if you have some other bugs consider switching to `PRINT_MODE:STANDARD` in `init.txt` config file.

# Configuration, modding, tileset etc

Nothing special here. Just remember that all of your game files (including saves!) are now inside Dwarf Fortress.app
and you can access them via `Show Package Contents` context menu option.

There is no perfect-for-everyone config. Suggested colorscheme and tileset can be found in `optional` directory.
This is very close to the vanilla Dwarf Fortress but looks much better on my macbook.

# Supported versions

Application bundle tested with vanilla 0.34.11 version of the game. Other versions should work as well.


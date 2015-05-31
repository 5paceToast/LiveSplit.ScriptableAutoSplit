LiveSplit Module
================
Scriptable Auto Split
---------------------

This is a module for LiveSplit. It defines ASL, the Auto Split Language.
If you downloaded Livesplit off the site, you already have it.
It allows users to define automatic split behaviors for their games.

### Quickstart ###
1. Get an ASL script.
2. Edit your splits (if needed) as per the script's documentation.
3. Edit your layout and add a Control->Scriptable Auto Splitter component.
4. In Layout Settings->Scriptable Auto Splitter, select the ASL script.

From now on, whenever you have your splits open and you start the game, the autosplitter will do (some) work for you.

### Capabilities ###
This module is capable of the following:

- Detecting when you start a run
- Detecting when you reset a run
- Detecting when to split
- Removing loading times
- Using the game to measure in-game time

To achieve this, the module reads memory addresses found within games to see the in-game state.

### Writing Your Own ###
Please refer to Scripts/Writing.md and examples in the Scripts folder to see how to write your own ASL scripts.

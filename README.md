# Steam Summer Monster Minigame Auto Upgrade Script #

This is a fork of [meishuu's Auto Upgrade Script](https://gist.github.com/meishuu/f83ee1de2992d5fc656c) to allow for the use of Tampermonkey and Greasemonkey.

## Installation ##

### Tampermonkey ###

1. Open Tapermonkey's dashboard.
2. Click on the `Utilities` tab on the right.
3. Paste `https://raw.githubusercontent.com/pBun/steamSummerMinigameUpgrades/master/upgradeManager.js` into the text area, and click `Import`.
4. When the editor has loaded, click `Install` (*NOT* `Process with Chrome`).

### Greasemonkey ###

1. Navigate to `https://raw.githubusercontent.com/pBun/steamSummerMinigameUpgrades/master/upgradeManager.js`.
2. Right click on the page, and click `Save Page As`.
3. While Firefox is still open, open a File Manager of any sort, and navigate to the directory you saved the script.
4. Drag & drop the script file onto the Firefox window.
5. Press `Install`.

### Manual ###

##### Chrome #####
1. Open https://raw.githubusercontent.com/pBun/steamSummerMinigameUpgrades/master/upgradeManager.js
2. Select All, Copy.
3. Navigate to `http://steamcommunity.com/minigame/` and join or start a game.
4. Press `Ctrl + Shift + J`.
5. Paste into the javascript input, and hit `Enter`.

##### Firefox #####
1. Open https://raw.githubusercontent.com/pBun/steamSummerMinigameUpgrades/master/upgradeManager.js
2. Select All, Copy.
3. Navigate to `http://steamcommunity.com/minigame/` and join or start a game.
4. Press `Ctrl + Shift + K`.
5. Paste into the javascript input, and hit `Enter`.

##### Internet Explorer / Microsoft Edge #####
1. Open https://raw.githubusercontent.com/pBun/steamSummerMinigameUpgrades/master/upgradeManager.js
2. Select All, Copy.
3. Navigate to `http://steamcommunity.com/minigame/` and join or start a game.
4. Press `F12` and navigate to the `Console` tab.
5. Paste into the javascript input, and hit `Enter`.

To stop the manual script, type `window.clearTimeout(window.SteamDB_Minigame_Timer);` into the console and hit `Enter`.

The game should now play itself, you should leave it running in the background. If you're not sure if it is auto-playing, try changing lanes. If it jumps back almost immediately, it's working.

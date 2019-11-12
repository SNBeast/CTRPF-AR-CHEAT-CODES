# [Database] CTRPF AR CHEAT CODES

# Notice

Hello, it's the new-new, unofficial owner of this archive ;P. I am keeping this repo up to date with the cheats in Sharkive and Checkpoint (whichever is newer at time of checking), and updating it for readability and pushing the recommended way of usage. This is an individual effort, and do not expect it to last a seriously long time. This is provided solely for convenience as the cheats here could just be updated by downloading Sharkive's source, copying the 3ds folder, and renaming it to "cheats" and dragging it to your SD root, or doing the same with Checkpoint except the 3ds folder is within the Sharkive folder.

Thank you to JourneyOver for the original repo, without which I wouldn't know that there was a version of Luma3DS 9.1 with the cheat loader (since 9.1 and above is what can load on FIRM 11.8+), and thank you to iSharingan for your earnest attempt to have the repo last a little longer.

<b>[Here's Sharkive for those wanting to contribute there, too](https://github.com/FlagBrew/Sharkive)</b>

## How to use

### Using Luma3DS with Plugin Loader (recommended)

1. Download `Luma3DS 9.1 - Plugin loader.zip` & `ActionReplay.zip`, and insert the 3DS's SD into the PC.

- `ActionReplay.zip` is in this repository or you can download from [here](http://gbatemp.net/threads/ctrpluginframework-blank-plugin.487729/). `Luma3DS 9.1 - Plugin loader.zip` is in this repository and not in the above post (which still has an outdated build not compatible with newer System Menus).

2. Make sure you already installed the latest `Boot9strap` and `Luma CFW` and have a firmware of 11.4 or higher.
3. Rename any existing `boot.firm` in the root of your SD card to `boot.firm.bak` in case you want to go back, then drag the `boot.firm` from `Luma3DS 9.1 - Plugin loader.zip` into the root of your SD card
4. 
 - If you want the cheats for all the games and generally want everything easier on you (recommended obviously):
   - I. Place the contents from `ActionReplay.zip` into `sd:/luma/plugins/ActionReplay/`.
   - II. Download this repo and copy the `cheats` folder to `sd:/`.
  
 - If you want a specific game's cheats and want to make this process hard on yourself:
   - I. Find the game's title ID. You can find the title id of many games [here](http://www.3dsdb.com/) or by doing some shenanigans in GodMode9, but cleaning up this README is already above my paygrade and you shouldn't be following this path anyway. :P
   - II. Place the contents from `ActionReplay.zip` into `sd:/luma/plugins/<Title ID>/`, and rename `ActionReplay.plg` to `plugin.plg`
   - III. Download this repo and copy the `<Title ID>.txt` in the `cheats` folder to `sd:/luma/plugins/<Title ID>/`, along side `plugin.plg` from step #II and rename the `<Title ID>.txt` you just copied over to `cheats.txt`.

5. Safely eject the SD card, insert it in the 3DS, and start the system.

6. Use your button combo to load up `rosalina menu` (default is usually `L+Down+select`) and enable `plugin loader` if it isn't already and then load up your game

- If you get a green screen during load then it worked
- To open CTRPluginFramework menu press `select` once in-game and click on `Action Replay` button to see the cheats.

\--

- Note: The plugin loader is automatically enabled on Old3DS because Mode3 games needs it.
- Note: On N3DS, you have to enable the plugin loader from Rosalina, and you can disable it too. You can't disable it for Mode3 games though.

### Using BOOTNTR

 You'll need to know the TitleID of your game. [This site](http://www.3dsdb.com/) may have it. If not, there's some shenanigans you can do in GodMode9 to get it, but cleaning up this README is already above my paygrade :P.

- If you decide to want to use `LUMAS3DS 9.1 Plugin Loader` alongside with `BOOTNTR` follow from the first step otherwise start at the second step!

1. Make sure to disable the plugin loader from Rosalina if you're using the `boot.firm` of `Luma3DS with Plugin Loader`
2. Download `ActionReplay.zip`

- Included in this repository or you can download from [here](http://gbatemp.net/threads/ctrpluginframework-blank-plugin.487729/)

3. Make sure you already installed the latest `Boot9strap` and `Luma CFW` and have a firmware of 11.4 or higher.
4. Place the contents from `ActionReplay.zip` into `SD:/plugin/<Title ID of the game folder>/`
5. Either download or clone this repository or search in the cheats folder for the game you want to cheat on and download the `.txt` file in the folder
6. Move the `.txt` file to either

- `sd:/cheats/`
  - txt files are conveniently already named correctly if placing here
- or place along side `plugin.plg` from #4 and rename the `.txt` to `cheats.txt`

7. Open up BOOTNTR and let it do its thing.
8. Load up game

- if you get a green screen during load then it worked
- To open CTRPluginFramework menu press `select` once in-game and click on `Action Replay` button to see the cheats.

## How To Add Cheats Using CTRPF AR On 3DS

After following either of the above you can look at this [video](https://www.youtube.com/watch?v=c2258P9wKkA) to see how to use the editor and create codes and/or you can follow below.

1. Open `CTRPF AR`

- `SELECT` is default

2. Press `ActionReplay`
3. Press the `Circled Plus Icon`
4. Press `Code`
5. Name your Cheat
6. Press the `Pencil Icon` on your currently added cheat
7. Press `Code`
8. Press `L` or `R` to add a 1 line of code, Pressing `Y` will delete the currently chosen line of code

- While on the currently chosen line of code, Pressing `L` will add a 1 line of code `above it`, Pressing `R` will add a 1 line of code `under it`

9. Then type the code you want to add using the `Touch Screen`
10. For `N3DS` only: Pressing `ZL` Will `copy` the currently chosen line of code to be pasted using `L` or `R`, And Pressing `ZR` will `Clear the Clipboard`

- which is the code that you copied

11. When done Adding/Editing code, Press `B` to go back and Press `A` to `Mark a Check/Activate` the cheat, and leave the cheat menu and see if the cheat works
12. Also there's a `Help` on the `Options` inside the `Code Editor` in case you didn't notice it

## If you wish to contribute

- codes that the CTRPF AR supports(Same as Gateshark but with more options!): [link](https://github.com/SNBeast/CTRPF-AR-CHEAT-CODES/blob/master/ActionReplayCodeTypes.txt)

1. Fork repository
2. Add Cheats / Make changes to cheats / Other
3. Once done send a pull request back to this repository

or

1. Create an issue!

- NOTE: I didn't create these cheats, and some cheats might not work.
  - If a cheat is not working, it just means that the cheat is wrong: no support will be done for cheats not working, I'm not here to fix all cheats, if you need help with broken codes either make an issue or add a comment in this [thread](https://gbatemp.net/threads/database-ctrpf-ar-cheat-codes.493220/) and somebody may be able to help you. Thank you!

## FAQS

1. Where can I put my cheat codes?

- Put them inside a text file called `cheats.txt` or `<Title ID of the game>.txt`.

2. Where should I put my `cheats.txt` or `<Title ID of the game>.txt`?

- Put them in `SD/plugin/<Title ID of the game folder>/cheats.txt`
- If you're using the Luma Plugin Loader, Put them in `sd:/luma/plugins/<title ID of the game folder>/cheats.txt`
- Or put them in `sd:/cheats/<Title ID of the game>.txt`

3. Can I use both `cheats.txt` and `<Title ID of the game>.txt` files at the same time?

- No, you don't/shouldn't use both if you already have 1 .txt file for the game in one of the directories. You only need either a `cheats.txt` or `<Title ID of the game>.txt` for a game not both.

4. Why isn't the plugin working?

- `LUMA3DS 9.1 Plugin Loader` only recognises `CTRPF (AR) Plugins` called `plugin.plg` at `sd:/plugin/<title ID of the game folder/` and `ActionReplay.plg` at `sd:/luma/plugins/ActionReplay`
- Make sure your using only 1 `CTRPF (AR) Plugin`! And No Other Plugins included alongside it! (Such as `Gateshark2NTR`, `libshark2NTR` or any other `Plugins`).
- If it gives you an error, try Deleting the `CTRPFData.bin` if it exists.
- If by chance you can't get `CTRPluginFramework` to come up after loading the game and having `plugin loaded` show, try using the `ActionReplay_ALT`.

5 This repo doesn't have cheats for the game I want!

- You can try [Max Cheats](https://www.max-cheats.com) or [GameHacking](https://gamehacking.org/system/3ds) and see if they possibly have it

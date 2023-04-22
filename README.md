# <img src="https://i.imgur.com/FVFGXkr.png" width="24" height="24"> SR3MP Revamp

SR3MP:Revamp is a new version of my original project "SR3MP" with a lot of improvements but incomplete for now.

# Features

- **F8** to open console.
- **DELETE** to unload the mod (only for debug purposes, it will not be available in the final release) (Only work on NON CEF build)
- **F1** to enable/disable no clip.

# Build

- Make sure you have the latest version of [Visual Studio 2022](https://visualstudio.microsoft.com/fr/vs/whatsnew/)
- Download the [latest SR3MP release](https://github.com/SR3-MP/SR3MP-Revamp/releases)
- Download release & source code
- Extract the source code anywhere on your computer
- Extract the "Build" folder from the release into the source code
- You can now open the project through **SR3MP_Revamp.sln**
- If you want to switch between different build types, you can edit defines values here:

<img src="https://i.imgur.com/SVVVtO2.png">
<img src="https://i.imgur.com/ranBmOf.png">

# Preview

<p align="center"><img src="https://i.imgur.com/0FkisxD.png"></p>
<p align="center"><img src="https://i.imgur.com/ZWYAp2N.jpg"></p>
<p align="center"><img src="https://i.imgur.com/BY6mJOA.jpg"></p>

# Credits

• <a href="https://github.com/K3rhos">@K3rhos</a> (I made the entire project base, including programming, design & arts)<br>
• <a href="https://github.com/NEZORTEK">@NEZORTEK</a> (For giving me some ideas during the development and some scripts)<br>
• <a href="https://github.com/RootKiller">@RootKiller</a> (<a href="https://github.com/RootKiller/sr3mp-Abandoned/">SR3MP abandoned project</a>.)<br>
• <a href="https://github.com/MrReekoFTWxD">@MrReekoFTWxD</a> (<a href="https://github.com/MrReekoFTWxD/SR3R">SR3R project</a>.)<br>

# TODO List

- [x] Basic scripting functions (Get/edit entities health, xp, money, etc...)
- [x] Pools managers (Get world entities, players, peds, vehicles and more...)
- [x] Patches (Removed intros, save warning, save & load game, map borders limitation etc...)
- [x] Debug (Debug menus & features to test stuff in the game)
- [x] ImGUI integration with DirectX render (Debug console/menus, etc...)
- [x] CEF integration with DirectX render (Custom main menu, loading/removing browsers, etc...)
- [x] Discord RPC
- [x] Inputs (Custom inputs hook + Xinput support + Game native inputs functions)
- [x] Game config variables editing
- [x] LUA scripting integration (Client side)
- [ ] LUA scripting integration (Server side)
- [ ] Server build
- [ ] Multiplayer stuff (Players sync, vehicles sync, etc...)
- [ ] Text Chat
- [ ] Voice Chat

# C2M IPS-patching Mod
This is a modded version of the Classic2Magic `c2m_gameprep` script that enables .IPS softpatching. This allows you to run fantranslations or romhacks while using your SFC and SNES cartridges.

Given the recent surge in fan translations, someone'll probably find this useful. I made this a long time ago, and I've had no issues with it at all, but it's probably not perfect.
It's designed for use with an actual SNES Classic, so if you're using your C2M in PC mode via `C2M Reader`, this probably won't be of much use to you. I think I briefly used it with an R36s back in March, and it did work, but it's not the intended use case.

# How to use it

1) Installing - Replace the `c2m/init/c2m_gameprep` file on your USB stick with the one provided.
2) Check your game names - Navigate through the cartdumps folder to get the names of your games. An example is `1BE359AB_DRAGONQUEST5.sfc`. These will be important.
3) Preparing your patches - Patches must be for the unheadered version of a game. If the patch you wish to use expects a headered game, you can use a program named `ipsbehead` to fix it.
4) Adding your patches - The .ips file must share the same name and location as the game dump. For `c2m/cartdumps/snes/1BE359AB_DRAGONQUEST5.sfc`, you'd want `c2m/cartdumps/snes/1BE359AB_DRAGONQUEST5.ips`.
5) Boot up the game! - I'm not certain if the stock emulator has a softpatching feature. I've always used the SNES Faust Xtreme core. On launch, you should see a message saying that the game has been patched. 



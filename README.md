## For people looking for binaries

There's a better maintained fork with a release here: https://github.com/QuickNET-Tech/GTAO_Booster_PoC/releases

I will not be providing any builds. This is a research project, the code is for demonstration purposes only.

## PoC that fixes two GTA Online bugs and drastically improves load times for CPU-bound systems

All addresses hardcoded for Steam and RL versions 2215/1.53

This is a proof of concept, not meant for casual use

Modifying your game while in online mode might get your account suspended, proceed with care

## How to

* `git clone --recurse-submodules https://github.com/tostercx/GTAO_Booster_PoC`
* build the project with MSVC
* inject the DLL with your favorite injector while the game is starting up

Might have to wait a few seconds before injecting - the game needs to deobfuscate some parts of itself

## More details

[Writeup](https://nee.lv/2021/02/28/How-I-cut-GTA-Online-loading-times-by-70/)

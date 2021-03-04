## Project status

Hey 👋

As I'm currently getting some non-developer traffic I feel like I should make some things clear.

1. **This project is currently unmaintained** - I only put the code here to prove a point. The code is ugly and it's barely good enough to run. I won't be making any improvements or keeping it up to date.
2. **Not for casual use** - the instructions below are for developers. I'm not providing any builds/binaries or user support. Some common questions are answered in the issue section.
3. **Feel free to fork** - if you are a developer and would like to maintain a more up-to-date version feel free to make a fork.

There's a fork by QuickNET-Tech here: https://github.com/QuickNET-Tech/GTAO_Booster_PoC He already made several improvements. I have not verified his builds, use at your own risk, but the guy seems ok. It looks like due to the amount of traffic/spam I redirected there his issue section is currently closed (sorry QuickNET :/)

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

# ForgeSMP Client

The ForgeSMP Client is the Fabric mod for ForgeSMP, the Minecraft PvP server at **forgesmp.org**.

**It is strongly recommended for playing on ForgeSMP.** The server works without it, but the mod gives you your own
ability keys, a proper cooldown display and real screens instead of chest menus. It is the way the server is meant
to be played.

**[Download the latest version](https://github.com/NatureBanana/ForgeSMP-Client-Download/releases/latest)**

This repo is only for downloads. Every version is a jar attached to a release.

## What it adds

- **Ability keys.** Keys of their own for your Relic and Legendary abilities, plus two optional keys for the second
  abilities. They cast without dropping or swapping anything, so a drawn bow, crossbow, trident or spear keeps its
  charge. Bind them in Options > Controls > Key Binds > ForgeSMP.
- **Ability display.** Your abilities next to the hotbar as icons or bars, with seconds left, plus your meters, your
  combat tag timer and the debuffs on you. Move it, resize it, or turn it off.
- **Screens.** `/relic`, the temple altar, `/keybinds`, `/cosmetics` and the Forge station open as real screens
  instead of chest menus. Each one can go back to its chest menu.
- **Season stats and legendaries.** Your kills, deaths and tier history this season, and every legendary with who
  holds it.
- **Event timers.** A small timer for the Forge Drop, the Vault opening and the grace period once they are announced.
- **Death recap.** After a PvP death, who hit you in the last seconds, with what, and for how much.
- **Notices.** Small pop-ups for relic tier changes, the Forge, grace ending, combat log results and cosmetics
  unlocked.
- **Effects settings.** Fewer particles if your computer is slow, and a ForgeSMP volume slider for the server's own
  sounds.
- **Molten Wings.** Drawn on the player model itself, so they stay on the body every frame.
- **Quenched.** A free join effect: you join white-hot, fresh from the forge, and cool down over 3 seconds. Players
  without the mod see it cold and grey.
- **Glowing Forge Plus trim.** The Forge Plus armour trim glows: its molten cracks shine in the dark, and heat pulses
  out from the white-hot heart along them. On you and on everyone near you who wears it. Without the mod the trim is
  still there, just not glowing.
- **Ender Poison hearts.** When the Dragon Relic poisons you, your hearts and the effect icon turn purple instead
  of Wither's black, so you know what hit you. Without the mod it shows as ordinary Wither.
- **Update notice.** One line in chat when a newer version is out. The mod never checks the internet itself.

On any server other than ForgeSMP the mod does nothing and sends nothing.

**Client checks.** Installing the mod means you agree to client checks: when a ForgeSMP admin asks, the mod reports
which mods and resource packs your game is running. It never shares file paths, your account, chats, your IP or
anything outside the game.

## Requirements

- Minecraft Java **1.21.11**
- **Fabric Loader 0.19.5** or newer
- **Fabric API** for 1.21.11 (built against 0.141.6+1.21.11)
- Mod Menu is optional

## Install

1. Install Fabric Loader for 1.21.11 if you do not have it.
2. Download `forgesmp-client-<version>.jar` from the
   [latest release](https://github.com/NatureBanana/ForgeSMP-Client-Download/releases/latest).
3. Put it in your `mods` folder, with Fabric API.
4. Start the game and join **forgesmp.org**.

On Lunar Client, pick 1.21.11, open Mods in the settings and drag the jar in. Lunar has its own Fabric API, so do not
add another.

To update, replace the old jar in your `mods` folder with the new one.

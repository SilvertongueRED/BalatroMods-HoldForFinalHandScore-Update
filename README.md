# Hold For Final Hand Score

Updated fork of Wiwiweb's Hold For Final Hand Score for Balatro, working with current Steamodded and Lovely.

The hand score goes away too fast in vanilla, especially for big hands that increase the game speed a lot. This mod holds the screen so you can read your result.

## Install

1. Install [Steamodded](https://github.com/Steamodded/smods) and Lovely.
2. Download `HoldForFinalHandScore-vX.Y.Z.zip` from the [Releases page](../../releases).
3. Extract it and put the `HoldForFinalHandScore` folder in `%appdata%\Balatro\Mods`. (Or clone this repo straight into that folder.)

## What it does

* Resets game speed acceleration right before the final Chip X Mult.
* Pauses 1.5 seconds (affected by game speed) for the final Chip X Mult, before it turns into the final hand score. The pause is queued after the deck effect, so Plasma Deck's balancing is shown first.
* Pauses for the final hand score before it gets added to the round score. It waits for the flames to die down (up to a maximum of 6 seconds), or if there are no flames, it waits 1 second.
* Deck effects (Plasma, Anaglyph) pass through untouched, and NaN or naneinf scores cannot softlock the game.
* Pause times and on/off toggles are in the mod's config tab.

## Credits

Original mod by [Wiwiweb](https://github.com/Wiwiweb/BalatroMods). Updated by SilvertongueRED. See LICENSE.

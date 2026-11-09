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

---

<!-- other-mods:start -->
## More from SilvertongueRED

**Fit to Screen (Menu Resizer) is now on Nexus Mods:** [nexusmods.com/balatro/mods/1001](https://www.nexusmods.com/balatro/mods/1001). It stops tall pause menus and sidebars from being cut off at the top and bottom of your screen.

### See my other mods and forks of other people's mods

- [Balatro-Fit-To-Screen-Menu-Resizer-](https://github.com/SilvertongueRED/Balatro-Fit-To-Screen-Menu-Resizer-) ([Nexus Mods](https://www.nexusmods.com/balatro/mods/1001)) - stops tall pause menus and sidebars from being cut off at the top and bottom of your screen
- [Balatro-Mod-Search-and-Sort](https://github.com/SilvertongueRED/Balatro-Mod-Search-and-Sort) ([Nexus Mods](https://www.nexusmods.com/balatro/mods/984)) - search, filter and sort the Mods menu without messing up the load order
- [Balatro-Mod-Updater](https://github.com/SilvertongueRED/Balatro-Mod-Updater) ([Nexus Mods](https://www.nexusmods.com/balatro/mods/1002)) - keeps your mods, Steamodded and Lovely up to date, with backups and a rescue screen when an update breaks the game
- [Balatro-SaveRewinder-Config-Fix](https://github.com/SilvertongueRED/Balatro-SaveRewinder-Config-Fix) - Save Rewinder fork with a config fix: automatic save points and one key to rewind (a fork of [liafonx/Balatro-SaveRewinder](https://github.com/liafonx/Balatro-SaveRewinder))
- [Trance-Active-and-Updated](https://github.com/SilvertongueRED/Trance-Active-and-Updated) - colour and font manager that recolours the whole game, maintained fork (a fork of [SpectralPack/Trance](https://github.com/SpectralPack/Trance))
- [Balatro-Preview-Accuracy-Update](https://github.com/SilvertongueRED/Balatro-Preview-Accuracy-Update) - previews the score and dollars you will get from the selected cards, accuracy update (a fork of [DivvyCr/Balatro-Preview](https://github.com/DivvyCr/Balatro-Preview))
- [Main-Menu-Theme-Selector](https://github.com/SilvertongueRED/Main-Menu-Theme-Selector) - choose your main menu colours, background theme and title logo (a fork of [EmperorGesar/Balatro-Colour-Selector](https://github.com/EmperorGesar/Balatro-Colour-Selector))
- [Better Mouse and Gamepad (bmag)](https://github.com/SilvertongueRED/bmag) - bind any key or button to quick actions like multiselect, easier on your hands (a fork of [uptudev/bmag](https://github.com/uptudev/bmag))
- [Balatro-Music-Selector-Fixes-and-Features](https://github.com/SilvertongueRED/Balatro-Music-Selector-Fixes-and-Features) - pick extra soundtracks or your own music without installing all of Cardsauce (a fork of [DZAladan/Balatro-Music-Selector](https://github.com/DZAladan/Balatro-Music-Selector))
<!-- other-mods:end -->

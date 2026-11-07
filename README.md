# steam-game-mode-custom-home

A small collection of standalone CSS Loader themes for Steam Game Mode / Big Picture. Each theme does exactly one thing and appears as its own entry in the CSS Loader theme list, enabled with that entry's toggle; there are no extra options inside — flip it on and the preset applies.

[中文说明 / Chinese README](README.zh-CN.md)

## Recommended companion

The tab-hiding rule used by `Recent Games At Bottom` follows the approach of [No Home Tabs by Sims](https://deckthemes.com/themes/view?themeId=1f13929d-cb5b-4ab9-985f-a69504e055fe), a third-party DeckThemes theme from 2023 that is not published by this repository's author. Linked for reference only.

## Themes

| Theme | What it does | Version |
| --- | --- | --- |
| [Hide Friends Playing](Hide%20Friends%20Playing/) | Hides the friend avatars Steam draws on game tiles when friends are playing that game. | 1.0.0 |
| [Recent Games At Bottom](Recent%20Games%20At%20Bottom/) | Docks the Recent Games row, with its name and playtime labels, to the bottom of the home screen. | 1.0.2 |
| [Titles Above Cards](Titles%20Above%20Cards/) | Moves game titles above the tiles and hides the now redundant Recent Games heading. | 1.0.0 |

> **Note**: enabling `Recent Games At Bottom` hides the home tabbed content area below the docked row — the "Recently Updated" shelves (and anything else that normally sits under Recent Games) are removed entirely, so they no longer show through or overlap the cards. Turn the theme off to get them back.

## Install

### From a release zip (recommended)

1. Download the zip for the theme you want from the [latest release](../../releases/latest).
2. In CSS Loader (Decky plugin) open **Themes** → **Install from file** and pick the zip.
3. The theme appears in the list as its own entry with a toggle; switch it on.

### Manually

Copy the theme folder (for example `Hide Friends Playing/`) into `~/homebrew/themes/` on the Steam Deck, then reload CSS Loader. Each folder with a `theme.json` shows up as a separate theme entry.

## Credits

These themes are derived from **tvdeck** (https://github.com/redsoap-blip/tvdeck), which is itself derived from **tvOS Deck** by K€YOZ (https://github.com/zoyekerako/tvos-deck), both released under the MIT License. The upstream copyright notice is reproduced in [LICENSE](LICENSE).

## License

MIT — see [LICENSE](LICENSE).

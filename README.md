# steam-game-mode-custom-home

A small collection of standalone CSS Loader themes for Steam Game Mode / Big Picture. Each theme does exactly one thing, installs on its own, and has no options — flip the toggle and it applies.

[中文说明 / Chinese README](README.zh-CN.md)

## Recommended companion

These three themes are the individual features taken out of [tvdeck](https://deckthemes.com/themes/view?themeId=1f13929d-cb5b-4ab9-985f-a69504e055fe), the full home-screen overhaul they were extracted from. They work on their own, but they are designed to sit on top of tvdeck and look best that way — install tvdeck from DeckThemes, then add only the pieces you want as separate toggles here.

If you do run both, turn **off** the matching options inside tvdeck (`Hide friends playing`, `Recent Games At Bottom`, `Titles Above Cards`) and let these standalone themes provide them instead. Enabling both copies at once stacks the same rules twice, which gains nothing and makes it harder to tell which toggle is responsible.

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

The zip already has the right layout (`<Theme Name>/theme.json`, `css/…`, `LICENSE`), so CSS Loader can install it directly.

### Manually

Copy the theme folder (for example `Hide Friends Playing/`) into `~/homebrew/themes/` on the Steam Deck, then reload CSS Loader. Each folder with a `theme.json` shows up as a separate theme entry.

## Using alongside tvdeck

These themes are extracted from [tvdeck](https://github.com/redsoap-blip/tvdeck) and can be enabled at the same time as it, but the results overlap:

- `Hide Friends Playing`, `Recent Games At Bottom` and `Titles Above Cards` correspond 1:1 to the tvdeck options of the same names. Enabling both the standalone theme and the tvdeck option is harmless but redundant — pick one.
- If you keep tvdeck's own option on, the standalone theme adds nothing; if you turn the tvdeck option off and the standalone theme on, the result is the same.
- `Recent Games At Bottom` and `Titles Above Cards` both reposition the same carousel. Enabling both is supported (tvdeck ships them together), but the labels end up above the docked row.

## Credits

These themes are derived from **tvdeck** (https://github.com/redsoap-blip/tvdeck), which is itself derived from **tvOS Deck** by K€YOZ (https://github.com/zoyekerako/tvos-deck), both released under the MIT License. The upstream copyright notice is reproduced in [LICENSE](LICENSE).

## License

MIT — see [LICENSE](LICENSE).

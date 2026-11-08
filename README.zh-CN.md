# steam-game-mode-custom-home

一组面向 Steam 游戏模式 / 大屏幕模式的独立 CSS Loader 小主题。每个主题只做一件事，装好后会作为独立条目出现在 CSS Loader 的主题列表里，用条目自带的开关启用或停用。

[English README](README.md)

## 主题列表

| 主题 | 作用 | 版本 |
| --- | --- | --- |
| [Hide Friends Playing](Hide%20Friends%20Playing/) | 隐藏游戏卡片上「好友正在玩」的小头像。 | 1.0.0 |
| [Recent Games At Bottom](Recent%20Games%20At%20Bottom/) | 把「最近游戏」一行（含名称与时长标签）贴到主界面底部。 | 1.0.2 |
| [Titles Above Cards](Titles%20Above%20Cards/) | 把游戏标题移到卡片上方，并隐藏此时多余的「最近游戏」标题。 | 1.0.0 |
| [Clean Gameview C](Clean%20Gameview%20C/) | 清理游戏内界面：调整播放栏、游戏头图与 Logo，可切换播放栏样式、对齐方式，并可选显示 Steam Cloud 标识。 | 1.7.1 |

> **注意**：`Recent Games At Bottom` 开启后会把 Recent Games 下方的整个 Home tabs 内容区隐藏掉——原本那排「最近已在此设备上更新」等 shelf 会被整体移除，所以不会再从卡片下面透出或叠在一起。关掉主题即可恢复。

## 安装

### 用 Release 里的 zip（推荐）

1. 从[最新 Release](../../releases/latest) 下载对应主题的 zip。
2. 在 CSS Loader（Decky 插件）里打开 **Themes** → **Install from file**，选择该 zip。
3. 主题会以独立条目出现在列表里并带开关，打开即可。

### 手动安装

把主题目录（例如 `Hide Friends Playing/`）整个复制到 Steam Deck 的 `~/homebrew/themes/`，然后重新加载 CSS Loader。每个含 `theme.json` 的目录都会成为列表中的一个独立主题。

## Credits

这些主题派生自 **tvdeck**（https://github.com/redsoap-blip/tvdeck），而 tvdeck 又派生自 K€YOZ 的 **tvOS Deck**（https://github.com/zoyekerako/tvos-deck），两者均以 MIT 协议发布。上游版权声明完整保留在 [LICENSE](LICENSE) 中。

`Recent Games At Bottom` 用到的隐藏 tab 规则沿用了 [No Home Tabs by Sims](https://deckthemes.com/themes/view?themeId=1f13929d-cb5b-4ab9-985f-a69504e055fe) 的做法，那是 2023 年发布的第三方 DeckThemes 主题，并非本仓库作者发布。

`Clean Gameview C` 基于 [Clean Gameview by SuchMeme](https://deckthemes.com/themes/view?themeId=a9776f60-2724-4ff0-824b-e1f82a04688e)，那是第三方 DeckThemes 主题，并非本仓库作者发布。

本项目还参考了 [Switch Like Home by Sims](https://deckthemes.com/themes/view?themeId=9ac2bf60-66c5-4f50-aa6b-f897465ba328)（v1.4，2024 年）与 [No Friend Playing Icon by Luna-Terra](https://deckthemes.com/themes/view?themeId=88363437-0fc3-44f7-9ae4-0ced63893aca)（2025 年），两者同为第三方 DeckThemes 主题，均非本仓库作者发布。

## License

MIT，见 [LICENSE](LICENSE)。

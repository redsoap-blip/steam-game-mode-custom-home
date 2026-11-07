# steam-game-mode-custom-home

一组面向 Steam 游戏模式 / 大屏幕模式的独立 CSS Loader 小主题。每个主题只做一件事，可以单独安装，没有开关项——打开主题开关即生效。

[English README](README.md)

## 主题列表

| 主题 | 作用 | 版本 |
| --- | --- | --- |
| [Hide Friends Playing](Hide%20Friends%20Playing/) | 隐藏游戏卡片上「好友正在玩」的小头像。 | 1.0.0 |
| [Recent Games At Bottom](Recent%20Games%20At%20Bottom/) | 把「最近游戏」一行（含名称与时长标签）贴到主界面底部。 | 1.0.1 |
| [Titles Above Cards](Titles%20Above%20Cards/) | 把游戏标题移到卡片上方，并隐藏此时多余的「最近游戏」标题。 | 1.0.0 |

## 安装

### 用 Release 里的 zip（推荐）

1. 从[最新 Release](../../releases/latest) 下载对应主题的 zip。
2. 在 CSS Loader（Decky 插件）里打开 **Themes** → **Install from file**，选择该 zip。
3. 主题会以独立条目出现在列表里并带开关，打开即可。

zip 内部已经是 `主题名/theme.json`、`css/…`、`LICENSE` 的结构，CSS Loader 可直接安装。

### 手动安装

把主题目录（例如 `Hide Friends Playing/`）整个复制到 Steam Deck 的 `~/homebrew/themes/`，然后重新加载 CSS Loader。每个含 `theme.json` 的目录都会成为列表中的一个独立主题。

## 与 tvdeck 同时启用

这些主题提取自 [tvdeck](https://github.com/redsoap-blip/tvdeck)，可以与它同时启用，但效果会重叠：

- `Hide Friends Playing`、`Recent Games At Bottom`、`Titles Above Cards` 与 tvdeck 中同名开关一一对应。同时打开独立主题和 tvdeck 对应开关不会有副作用，只是重复——选一个即可。
- 保留 tvdeck 自己的开关，独立主题不会带来额外变化；关掉 tvdeck 开关、打开独立主题，效果一样。
- `Recent Games At Bottom` 与 `Titles Above Cards` 调整的是同一个轮播区域。两者同时启用是支持的（tvdeck 本身就是这么组合的），只是标题会落在贴底的那一行上方。

## Credits

这些主题派生自 **tvdeck**（https://github.com/redsoap-blip/tvdeck），而 tvdeck 又派生自 K€YOZ 的 **tvOS Deck**（https://github.com/zoyekerako/tvos-deck），两者均以 MIT 协议发布。上游版权声明完整保留在 [LICENSE](LICENSE) 中。

## License

MIT，见 [LICENSE](LICENSE)。

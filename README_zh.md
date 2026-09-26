[日本語](README_ja.md) | [English](README_en.md) | [한국어](README_ko.md) | **中文**
# Sephiria-ExtraCharacters

这是一个为塞菲莉娅添加多种新服装的MOD。
**今后将通过更新陆续追加更多服装。**

**各服装的详细数值以及过往更新内容，请查看[更新日志](Patchlog_zh.md)！**

## 特点

* 为塞菲莉娅添加新的服装
* 每套新增服装都拥有各自独特的新效果和神器

## 新增角色

目前已添加以下4名角色。
各角色的详细数值请在游戏内或[更新日志](https://github.com/ao-408/Sephiria-ExtraCharacters/blob/main/patchlog_zh.md)中查看！

### ![服装预览](images/Mymelody/Mymelody.png) 美乐蒂

### ![服装预览](images/Sans/Sans.png) Sans

### ![服装预览](images/Kirby/Kirby.png) 卡比

### ![服装预览](images/Dummy/Dummy.png) 假人酱

## 安装方法

### 关于下载文件

本MOD提供两种ZIP文件，请根据你的环境选择其中一种下载。

* **尚未安装ModMaker Runtime** → `ExtraCharactersMOD-x.x.x-withRuntime.zip`（包含ModMaker Runtime）
  该压缩包中包含最新版本的Runtime，无需额外操作。
* **已经安装ModMaker Runtime** → `ExtraCharactersMOD-x.x.x.zip`（不包含Runtime）
  **根据本AddOn的版本不同，可能需要更新ModMaker Runtime本身。** 如果你使用的Runtime版本过旧，AddOn可能无法正常运行。此时请安装包含Runtime的版本（`-withRuntime.zip`），或将Runtime更新到最新版本。

### 安装步骤

1. 根据上述说明，从[Releases](../../releases)下载对应的ZIP文件。
2. 解压ZIP文件。
3. 将其中的 `AddOns` 文件夹放置到与 `Sephiria.exe` 相同的目录下。

   * 如果已经存在 `AddOns` 文件夹，请将内容进行**覆盖/合并**。请不要直接替换整个文件夹，否则可能会导致其他AddOn被删除。建议只复制文件夹中的内容。
4. 启动游戏，确认新的服装已经添加。

## 注意事项

* 本AddOn仅用于添加新的服装，不会对现有服装或正常游戏流程造成任何影响。（例如，部分新服装会赋予新的神器，但这些神器不会在正常游戏中的奖励或商店中出现。）
* **本AddOn包含用于实现部分神器行为的自定义脚本（以C#编写的代码）。** 这些脚本通过ModMaker Runtime加载。
* 本AddOn不包含任何 `Sephiria` 游戏本体的资源或数据。请自行合法获取游戏本体。
* 本AddOn使用 [Sephiria-ModMaker](https://github.com/Xetsumei/Sephiria-ModMaker/tree/main) 制作。使用时请遵守ModMaker本身的使用条款及许可证。
* **多人游戏时，所有参与者都必须安装相同的 MOD。** 不支持仅部分玩家安装 MOD 的情况下进行游戏。
* 如果想暂时禁用 MOD，请在游戏中按下 `Esc` 键，然后在 ModMaker 的信息界面中将该 MOD 关闭（OFF）。
* 使用本AddOn所产生的一切风险由用户自行承担。

## 致谢

本AddOn使用了由Xetsumei开发的**Sephiria-ModMaker**制作。
衷心感谢Xetsumei公开并提供了如此优秀的工具！

## 反馈

如果你发现了Bug、有改进建议，或者想推荐新的服装，欢迎随时联系我们！

* **GitHub Issue**：请通过[这里](../../issues)提交反馈
* **Discord DM**：`a_o_b`

我们会认真查看每一条反馈，谢谢！

## 平衡性调整

新服装的调整目标是尽可能让其强度与现有服装保持在相近的水平。

如果你觉得某个服装过强或过弱，欢迎通过 [Issue](../../issues) 或 Discord 告诉我你的意见。我会将这些反馈作为后续数值调整的参考。

## 许可证

本AddOn的代码及配置文件以 [MIT License](LICENSE) 许可证公开。
请在该许可证允许的范围内使用。

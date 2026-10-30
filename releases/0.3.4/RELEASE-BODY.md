# FramePair 0.3.4

[English](#framepair-034) · [简体中文](#framepair-034简体中文)

FramePair 0.3.4 adds target output ratios, continuous Split cropping, and independent copies of the same photo, with improvements to the start window, recovery, and accessibility since 0.3.1.

## Changes

- Start from a compact import window with recent folders and an optional portrait or landscape output ratio; review ratio mismatches before export without blocking it
- Adjust Split framing in its own step: enable a continuous crop whose two halves match the target ratio, with movement, resizing, reset, keyboard control, and Undo / Redo
- Reuse a source photo through independent workspace copies, including in the same Merge, and choose a default processing mode for new entries
- Keep photo grids, window layouts, and previews readable at different window sizes; the four processing choices remain stable during rapid scrolling
- Recover from import and output-estimate failures, and edit a completed batch to export again with the existing file-safety checks
- Use File-menu import and export commands, and reorder output groups or operate Merge slots with VoiceOver
- Use a refreshed app icon with light and dark appearances

## Requirements and installation

- Apple Silicon Mac
- macOS 26.0 or later

Download `FramePair-0.3.4-macOS-arm64.dmg` from Assets, or use `FramePair-0.3.4-macOS-arm64.zip` as an alternative. Installation steps are in the [README](https://github.com/CedricChanning/FramePair#installation). Existing installations with in-app update support can check the official update channel from the application menu.

## Integrity

SHA-256 for `FramePair-0.3.4-macOS-arm64.dmg`:

```text
304a264ad873da5d8deceabd90b5b08435af4567222d8193744a116b2d9cf40d
```

SHA-256 for `FramePair-0.3.4-macOS-arm64.zip`:

```text
9ef8f4b82cd4785fa9b4c2ff958dc361fcca5ddb01e0ba8af30f9db3595cb0c7
```

The FramePair application and DMG are signed with Developer ID, notarized by Apple, and have their notarization tickets stapled. Source photos remain unchanged.

# FramePair 0.3.4（简体中文）

FramePair 0.3.4 新增目标输出比例、Split 连续裁剪与同一照片的独立副本，并汇总自 0.3.1 以来的启动页、恢复操作和辅助功能改进。

## 更新内容

- 从紧凑启动页访问最近文件夹，并按需选择横向或竖向目标输出比例；导出前可查看比例差异，提示不会阻止导出
- 在独立 Split 步骤中调整取景：主动开启连续裁剪，使左右两格各自符合目标比例，支持移动、缩放、重置、键盘操作及 Undo / Redo
- 通过独立工作区副本复用同一照片，也可将同源条目加入同一个 Merge；新增条目的默认处理方式可在 Settings 配置
- 改善不同窗口尺寸下的照片网格、布局和预览，快速滚动时四项处理方式保持稳定
- 导入或输出估算失败后可直接恢复；已完成批次可继续编辑并重新导出，沿用现有文件安全检查
- 通过 File 菜单导入与导出，使用 VoiceOver 调整输出组顺序和操作 Merge 槽位
- 更新应用图标，支持明暗外观

## 系统要求与安装

- Apple Silicon Mac
- macOS 26.0 或更高版本

从 Assets 下载 `FramePair-0.3.4-macOS-arm64.dmg`，也可使用备用安装包 `FramePair-0.3.4-macOS-arm64.zip`。安装步骤见 [README](https://github.com/CedricChanning/FramePair#安装)。已支持应用内更新的现有安装可以从应用菜单检查官方更新频道。

## 完整性

`FramePair-0.3.4-macOS-arm64.dmg` 的 SHA-256：

```text
304a264ad873da5d8deceabd90b5b08435af4567222d8193744a116b2d9cf40d
```

`FramePair-0.3.4-macOS-arm64.zip` 的 SHA-256：

```text
9ef8f4b82cd4785fa9b4c2ff958dc361fcca5ddb01e0ba8af30f9db3595cb0c7
```

FramePair 应用与 DMG 均使用 Developer ID 签名、通过 Apple 公证并装订票据。来源照片保持不变。

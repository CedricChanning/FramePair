# FramePair 0.3.5

[English](#changes) · [简体中文](#更新内容)

FramePair 0.3.5 lets photos with the same exact aspect ratio join a Merge at different pixel sizes, with per-photo resizing details and a setting that applies to the current batch.

## Changes

- Combine two or three photos with the same exact aspect ratio at different pixel sizes by enabling Allow Different Sizes in Merge in General Settings; larger photos are reduced to the smallest size in the group while preserving the full frame
- Review Downscaled labels in Merge Photos to see each affected photo’s dimensions before and after resizing
- Apply the setting to the current batch immediately; turning it off asks before ungrouping incompatible merges and keeps same-size merges intact

## Requirements and installation

- Apple Silicon Mac
- macOS 26.0 or later

Download `FramePair-0.3.5-macOS-arm64.dmg` from Assets, or use `FramePair-0.3.5-macOS-arm64.zip` as an alternative. Installation steps are in the [README](https://github.com/CedricChanning/FramePair#installation). Existing installations with in-app update support can check the official update channel from the application menu.

## Integrity

SHA-256 for `FramePair-0.3.5-macOS-arm64.dmg`:

```text
8775c8677e3ebea0750a3bd0d7bd82b3f148e978f532451e5fa7bb88f405acf8
```

SHA-256 for `FramePair-0.3.5-macOS-arm64.zip`:

```text
f5a672827b4bef62382d52051073d1b1183a937b4173e402df7b4a28751febeb
```

The FramePair application and DMG are signed with Developer ID, notarized by Apple, and have their notarization tickets stapled. Source photos remain unchanged.

## 更新内容

FramePair 0.3.5 允许精确同比例、不同像素尺寸的照片参与 Merge，提供逐张缩小详情，并使设置立即作用于当前批次。

- 在 General Settings 开启「允许 Merge 使用不同尺寸」后，可将精确同比例、不同像素尺寸的两张或三张照片拼合；较大照片按组内最小尺寸缩小，保留完整画面
- 在 Merge Photos 通过「已缩小」Label 查看受影响照片及其缩小前后尺寸
- 设置立即作用于当前批次；关闭时先确认是否解散不兼容组，同尺寸组保持不变

## 系统要求与安装

- Apple Silicon Mac
- macOS 26.0 或更高版本

从 Assets 下载 `FramePair-0.3.5-macOS-arm64.dmg`，也可使用备用安装包 `FramePair-0.3.5-macOS-arm64.zip`。安装步骤见 [README](https://github.com/CedricChanning/FramePair#安装)。已支持应用内更新的现有安装可以从应用菜单检查官方更新频道。

## 完整性

`FramePair-0.3.5-macOS-arm64.dmg` 的 SHA-256：

```text
8775c8677e3ebea0750a3bd0d7bd82b3f148e978f532451e5fa7bb88f405acf8
```

`FramePair-0.3.5-macOS-arm64.zip` 的 SHA-256：

```text
f5a672827b4bef62382d52051073d1b1183a937b4173e402df7b4a28751febeb
```

FramePair 应用与 DMG 均使用 Developer ID 签名、通过 Apple 公证并装订票据。来源照片保持不变。

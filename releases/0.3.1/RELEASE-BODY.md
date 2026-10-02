# FramePair 0.3.1

[English](#framepair-031) · [简体中文](#framepair-031简体中文)

FramePair 0.3.1 corrects small aspect-ratio differences even when a photo needs a few extra pixels, and makes source-photo removal easier to access.

## Changes

- Correct photos that are slightly above or below a built-in or custom aspect ratio by cropping excess pixels or repeating edge pixels to fill a small shortfall; previews and JPEG / PNG exports use the same corrected dimensions
- Auto Crop is now named Auto Ratio Correction, with details showing the cropped or added pixels on each affected edge
- Remove a source photo using the button at the top-right of its preview; the arrangement picker has its own row

## Requirements and installation

- Apple Silicon Mac
- macOS 26.0 or later

Download `FramePair-0.3.1-macOS-arm64.dmg` from Assets, or use `FramePair-0.3.1-macOS-arm64.zip` as an alternative. Installation steps are in the [README](https://github.com/CedricChanning/FramePair#installation). Existing installations with in-app update support can check the official update channel from the application menu.

## Integrity

SHA-256 for `FramePair-0.3.1-macOS-arm64.dmg`:

```text
e5ec1995ba2239443668f44e9ef19570a818e473441b4e3cc789f7c4f7c672d6
```

SHA-256 for `FramePair-0.3.1-macOS-arm64.zip`:

```text
59e8e3197f0f14e5c575e03759f7c0b388991cdaf9433a1bd9dcab8788558b4d
```

The FramePair application is signed with Developer ID and notarized by Apple. Source photos remain unchanged.

# FramePair 0.3.1（简体中文）

FramePair 0.3.1 使像素略少的近似比例照片也能校正为精确比例，并改善来源照片移除按钮的位置。

## 更新内容

- 接近内置或自定义比例的照片，无论像素略多还是略少，都可通过裁切或边缘像素复制补齐为精确比例；预览与 JPEG / PNG 输出使用一致的校正尺寸
- Auto Crop 更名为「自动比例校正」，详情分别显示各边实际裁切或补齐的像素
- 来源照片的移除按钮固定在预览右上角，处理方式选择器独占一行

## 系统要求与安装

- Apple Silicon Mac
- macOS 26.0 或更高版本

从 Assets 下载 `FramePair-0.3.1-macOS-arm64.dmg`，也可使用备用安装包 `FramePair-0.3.1-macOS-arm64.zip`。安装步骤见 [README](https://github.com/CedricChanning/FramePair#安装)。已支持应用内更新的现有安装可以从应用菜单检查官方更新频道。

## 完整性

`FramePair-0.3.1-macOS-arm64.dmg` 的 SHA-256：

```text
e5ec1995ba2239443668f44e9ef19570a818e473441b4e3cc789f7c4f7c672d6
```

`FramePair-0.3.1-macOS-arm64.zip` 的 SHA-256：

```text
59e8e3197f0f14e5c575e03759f7c0b388991cdaf9433a1bd9dcab8788558b4d
```

FramePair 应用使用 Developer ID 签名并经过 Apple 公证。来源照片保持不变。

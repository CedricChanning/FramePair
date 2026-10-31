# FramePair

[English](#framepair) · [简体中文](#framepair简体中文)

<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="assets/readme/hero-dark.png">
  <source media="(prefers-color-scheme: light)"
          srcset="assets/readme/hero-light.png">
  <img src="assets/readme/hero-light.png"
       alt="FramePair merges and splits a batch of photos into images ready to share."
       width="1600">
</picture>

FramePair is a native photo-arrangement app for Apple Silicon Macs. It turns local photos that have already been edited into finished images for phones and social platforms. A batch can combine JPEG, PNG, and single-image TIFF sources, then export the arranged results in one order as JPEG or lossless PNG.

All processing stays on the Mac. Original photos remain unchanged, and existing files are never silently overwritten. Before export, the final order, filenames, output format, and destination can be reviewed together.

[Download FramePair 0.3.5 DMG](https://github.com/CedricChanning/FramePair/releases/download/v0.3.5/FramePair-0.3.5-macOS-arm64.dmg) · [All releases](https://github.com/CedricChanning/FramePair/releases) · [Report an issue](https://github.com/CedricChanning/FramePair/issues)

## Core capabilities

- **Mix different arrangements in one batch**
  - Each photo can use its own arrangement: Direct keeps one photo as one output; Merge 2 and Merge 3 stack two or three photos vertically; Split produces consecutive left and right outputs from the visual center or a continuous crop chosen in its own editing step
  - Different arrangements can share one batch and continue through the same preview, ordering, naming, and export workflow
- **Reuse a photo in independent arrangements**
  - Duplicate Photo creates another workspace entry without copying the source file; each entry can use its own processing mode and Split crop, and entries from the same source can join one Merge
  - Choose a default processing mode in Settings for newly imported or duplicated entries
- **Choose a target ratio and adjust Split framing**
  - Set an optional portrait or landscape output ratio before import, and return to recently used folders from the compact start window
  - In Split Photos, enable cropping to move or resize one continuous frame whose two halves each match the target ratio; cropping supports reset, keyboard control, and Undo / Redo
  - Ratio warnings identify results that differ from the target without blocking export; changing the target requires a new batch
- **Explore the best composition in a dedicated merge view**
  - Merge Photos shows candidate photos and merge results together, with a larger result view for comparing combinations
  - An individual photo can be released and replaced, an empty position can be filled, and the top and bottom photos can exchange positions
  - Enable Allow Different Sizes in Merge in General Settings to combine photos with the same exact aspect ratio at different pixel sizes; larger photos are reduced to the smallest size in the group while preserving the full frame
  - The setting is off by default and applies to the current batch immediately; Downscaled labels show affected photos and their dimensions before and after resizing
- **Track pixel dimensions and aspect ratios throughout the workflow**
  - Source photos, arrangements, and Output Preview continue to show pixel dimensions and reduced aspect ratios for checking the final specification before export
  - Optional Auto Ratio Correction adjusts photos that are only slightly outside a built-in or custom ratio by cropping excess edge pixels or repeating edge pixels to fill a small shortfall, without scaling the original image or changing the source file
- **Finalize result order and sequential numbering before export**
  - Complete arrangements can be reordered by dragging in Output Preview; the two photos produced by Split always move as one group
  - Export follows the confirmed order and automatically numbers the files, with configurable filename prefix, starting number, and minimum digit count
- **Control output format, file size, and compression level**
  - A batch can mix JPEG, PNG, and single-image TIFF sources, then export all results as JPEG or lossless PNG
  - JPEG output can use a per-file size limit; before export, each result shows its estimated size and either Original, Maximum Quality, or the actual JPEG quality value

## Basic workflow

1. Optionally choose a target output ratio, then import local JPEG, PNG, or single-image TIFF photos from a chosen location or a recent folder
2. Choose Direct, vertical Merge, or Split for each entry; duplicate an entry when the same source is needed again
3. Confirm merge combinations and vertical order in Merge Photos, when needed
4. In Split Photos, keep the center split or enable a continuous crop that matches the target ratio
5. Check pixel dimensions, aspect ratios, export selection, and final order in Output Preview
6. Choose JPEG or PNG, filename settings, extension letter case, and the export folder
7. Review per-file estimates and start the export

## Local processing and file safety

Source photos are always read-only. FramePair does not modify, move, rename, or delete imported originals.

Every output is generated and checked before being written to its final destination. Existing destination files are not overwritten. Cancellation or any export failure stops the remaining work and rolls back outputs still owned by that run.

Valid RGB ICC information required to interpret photo pixels is retained without color-space conversion. EXIF, GPS, IPTC, XMP, and other camera privacy metadata are not copied to exported files.

## Requirements and formats

| Item | Supported |
|---|---|
| Mac | Apple Silicon |
| macOS | macOS 26.0 or later |
| Input | JPEG, PNG, single-image TIFF |
| Output | JPEG, PNG |
| Interface | English, Simplified Chinese |
| Processing | Local only |

TIFF is an input format only. HDR, Animated PNG, multi-page TIFF, transparent images, color-space conversion, cloud sync, and direct publishing to social platforms are outside the current scope.

## Installation

### DMG

1. Download `FramePair-0.3.5-macOS-arm64.dmg`
2. Open the disk image
3. Drag `FramePair.app` onto the Applications shortcut
4. Eject the disk image
5. Open FramePair from Applications

### ZIP

Download and extract `FramePair-0.3.5-macOS-arm64.zip`, then move `FramePair.app` into Applications.

GitHub also provides automatically generated Source code archives. These contain repository files, not a runnable FramePair application.

SHA-256 checksums and signing and notarization details for each installer are provided on its corresponding GitHub Release page.

## Application updates

FramePair can check the official update channel from the application menu. Daily checks are optional, and checking never automatically downloads or installs an update.

When a new version is available, the update window shows release notes in the macOS language. An update can be postponed or the current version can be skipped. Installation and restart remain unavailable while a photo batch is active.

## Repository scope

This public repository hosts official downloads, release notes, the update feed, and issue reports. FramePair source code is maintained separately and is not distributed here.

# FramePair（简体中文）

FramePair 是面向 Apple Silicon Mac 的原生照片编排工具，用于将已经完成后期处理的本地照片整理成适合手机与社交平台浏览的成片。一批照片可以混合使用 JPEG、PNG 与单图 TIFF 来源，完成编排后再按照统一顺序导出为 JPEG 或无损 PNG。

全部处理均在 Mac 本地完成。原照片保持不变，已有文件不会被静默覆盖；导出前可以统一确认结果顺序、文件名、输出格式和目标位置。

[下载 FramePair 0.3.5 DMG](https://github.com/CedricChanning/FramePair/releases/download/v0.3.5/FramePair-0.3.5-macOS-arm64.dmg) · [全部版本](https://github.com/CedricChanning/FramePair/releases) · [反馈问题](https://github.com/CedricChanning/FramePair/issues)

## 核心功能

- **同一批次灵活组合不同处理方式**
  - 每张照片可以独立选择处理方式：Direct 保持单张输出；Merge 2 与 Merge 3 分别将两张或三张照片上下拼合；Split 从视觉中心拆分，或在独立步骤中选择连续裁剪区域，产生连续的左右两张
  - 不同处理方式可以同时存在于一个批次，最终进入同一套预览、排序、命名和导出流程
- **为同一照片建立独立处理方案**
  - Duplicate Photo 会新增工作区条目，不复制磁盘原文件；每个条目可以使用自己的处理方式和 Split 裁剪，同源条目也能参与同一个 Merge
  - 可在 Settings 选择默认处理方式，用于之后导入或复制的条目
- **选择目标比例并调整 Split 取景**
  - 导入前可选择横向或竖向目标输出比例，也可从紧凑启动页返回最近使用的文件夹
  - 在 Split Photos 主动开启裁剪后，可移动或缩放一个连续框，使左右两格各自符合目标比例；支持重置、键盘操作及 Undo / Redo
  - 比例提示帮助识别与目标不一致的结果，但不会阻止导出；更换目标比例需要开始新批次
- **在独立拼合视图中探索最佳组合**
  - Merge Photos 同时显示候选照片与拼合结果，并提供较大的结果视图用于比较不同组合
  - 结果中的单张照片可以释放并重新补入，空缺可以回填，顶部和底部照片也可以交换位置
  - 在 General Settings 开启「允许 Merge 使用不同尺寸」后，可拼合精确同比例、不同像素尺寸的照片；较大照片按组内最小尺寸缩小，保留完整画面
  - 设置默认关闭，修改立即作用于当前批次；「已缩小」Label 显示受影响照片及其缩小前后尺寸
- **全程掌握像素尺寸与画面比例**
  - 来源照片、编排过程和 Output Preview 持续显示像素尺寸与约分比例，便于在导出前核对成片规格
  - 可选的自动比例校正会将与内置或自定义比例只有轻微偏差的照片校正为精确比例：裁去多余的边缘像素，或复制边缘像素补齐少量不足，不缩放原有画面，也不改变原文件
- **导出前确定成片顺序和连续编号**
  - 完整安排可以在 Output Preview 中拖动排序；Split 产生的左右两张始终作为一组移动
  - 导出时按照确认后的顺序自动连续编号，并可设置文件名前缀、起始编号和最少位数
- **控制输出格式、文件大小和压缩程度**
  - 同一批次可以混合导入 JPEG、PNG 与单图 TIFF，并统一导出为 JPEG 或无损 PNG
  - JPEG 输出可以设置逐文件大小上限；导出前会显示预计文件大小以及 Original、Maximum Quality 或实际 JPEG 质量值

## 基本流程

1. 按需选择目标输出比例，再从所选位置或最近文件夹导入本地 JPEG、PNG 或单图 TIFF 照片
2. 为每个条目选择保持原样、上下拼合或左右拆分；需要再次使用同一来源时复制条目
3. 有 Merge 条目时，在 Merge Photos 中确认照片组合与上下顺序
4. 在 Split Photos 保留居中拆分，或主动开启符合目标比例的连续裁剪
5. 在 Output Preview 中核对像素、比例、导出范围和最终顺序
6. 选择 JPEG 或 PNG、文件名、大小写扩展名和导出文件夹
7. 查看逐文件估算并开始导出

## 本地处理与文件安全

来源照片始终只读。FramePair 不会修改、移动、重命名或删除已经导入的原文件。

每个输出在正式写入前都会完成生成和复查。已有目标文件不会被覆盖。取消或任一导出失败会停止后续处理，并回滚仍属于本次执行的输出。

解释照片像素所需的有效 RGB ICC 色彩信息会被保留，FramePair 不进行色彩空间转换。EXIF、GPS、IPTC、XMP 及其他相机隐私元数据不会复制到导出文件。

## 支持环境与格式

| 项目 | 支持范围 |
|---|---|
| Mac | Apple Silicon |
| macOS | macOS 26.0 或更高版本 |
| 输入 | JPEG、PNG、单图 TIFF |
| 输出 | JPEG、PNG |
| 界面 | 英文、简体中文 |
| 处理位置 | 仅在本地完成 |

TIFF 仅作为输入格式，不作为输出格式。HDR、Animated PNG、多页 TIFF、透明图片、色彩空间转换、云同步和直接发布到社交平台不在当前范围内。

## 安装

### DMG

1. 下载 `FramePair-0.3.5-macOS-arm64.dmg`
2. 打开磁盘映像
3. 将 `FramePair.app` 拖到「应用程序」快捷方式
4. 推出磁盘映像
5. 从「应用程序」打开 FramePair

### ZIP

下载并解压 `FramePair-0.3.5-macOS-arm64.zip`，再将 `FramePair.app` 移入「应用程序」。

GitHub 还会自动提供 Source code 压缩包。这些压缩包只包含仓库文件，不是可运行的 FramePair 应用。

各版本安装包的 SHA-256 校验值与签名、公证信息见对应的 GitHub Release 页面。

## 应用更新

FramePair 可以从应用菜单检查官方更新频道。每日检查由使用者自行选择，检查过程不会自动下载或安装更新。

发现新版本后，更新窗口会按照 macOS 语言显示对应版本说明。更新可以稍后处理，也可以跳过当前版本。存在活动照片批次时，安装和重新启动会延后到当前批次结束之后。

## 仓库范围

本公开仓库用于提供官方下载、版本说明、更新清单和问题反馈。FramePair 源码在独立位置维护，不在此分发。

# FramePair 0.3

[English](#framepair-03) · [简体中文](#framepair-03简体中文)

FramePair 0.3 focuses on flexible photo arrangements and export preparation within one batch. Different photos can remain unchanged, be stacked vertically, or be split into left and right outputs, while final aspect ratios, ordering, numbering, and file sizes remain visible before export.

## Key updates

- Mix multiple arrangements in one batch: Direct keeps one photo as one output; Merge 2 and Merge 3 stack two or three photos vertically; Split divides one wide photo at its visual center into consecutive left and right outputs
- Compare candidate photos and merge results together in Merge Photos, replace an individual result photo, fill an empty position, and exchange the top and bottom photos
- Track pixel dimensions and aspect ratios from source photos through arrangement and Output Preview, making it easier to check the finished specification required by a social platform
- Optionally use Auto Crop to remove a few edge pixels when a photo is only slightly outside a common ratio, without scaling, padding, or changing the original file
- Reorder finished arrangements in Output Preview and export them with automatic sequential numbering; the two photos produced by Split always move as one group
- Apply a per-file JPEG size limit and review the estimated size and encoding quality before export to avoid excessive compression
- Mix JPEG, PNG, and single-image TIFF sources in one batch, then export the batch as JPEG or lossless PNG

## Other improvements

Photo cards and previews respond more consistently to the available window width. Photo Size can adjust the preview size across the main workflow without changing source or exported pixel dimensions.

The interface supports English and Simplified Chinese and adds in-app update checks. All photo processing remains local, source photos stay read-only, and existing destination files are never silently overwritten.

## Requirements

- Apple Silicon Mac
- macOS 26.0 or later

## Download and installation

Download `FramePair-0.3-macOS-arm64.dmg` from Assets. `FramePair-0.3-macOS-arm64.zip` is also available as an alternative; GitHub's automatically generated Source code archives are not runnable applications.

See the [README](https://github.com/CedricChanning/FramePair#readme) for complete installation steps and the product overview.

## Integrity

SHA-256 for `FramePair-0.3-macOS-arm64.dmg`:

```text
418e1331e48243608b169f685735fe61c977fa1f4ae86399c3321aa49d94599b
```

SHA-256 for `FramePair-0.3-macOS-arm64.zip`:

```text
87f0a00d72fd5de1f3047c931a83b429a3aaf6a871c9f9485d0cd9d2c3de4ba1
```

The FramePair application is signed with Developer ID, notarized by Apple, and distributed for Apple Silicon (arm64) Macs.

Installation or application issues can be reported through this repository's [Issues](https://github.com/CedricChanning/FramePair/issues).

# FramePair 0.3（简体中文）

FramePair 0.3 重点完善多张照片在同一批次中的灵活编排与导出准备。不同照片可以分别保持原样、上下拼合或左右拆分，并在导出前集中确认成片比例、顺序、编号和文件大小。

## 主要更新

- 同一批次可混合使用多种处理方式：Direct 将一张照片保持为一个输出；Merge 2 与 Merge 3 分别将两张或三张照片上下拼合；Split 从视觉中心将一张宽图分成前后连续的左右两张
- Merge Photos 同时显示候选照片与拼合结果，可替换结果中的单张照片、回填空缺，并交换顶部和底部位置以比较不同组合
- 来源照片、编排过程和 Output Preview 持续显示像素尺寸与画面比例，便于在导出前核对社交平台所需的成片规格
- 可选的 Auto Crop 会从中心移除边缘的少量像素，修正与常见比例只有轻微偏差的照片，不缩放、不补边，也不改变原文件
- Output Preview 支持拖动调整成片顺序；导出时按照确认后的顺序自动连续编号，Split 产生的左右两张始终作为一组移动
- JPEG 输出可设置逐文件大小上限，并在导出前显示预计文件大小及采用的编码质量，便于避免过度压缩
- 同一批次可混合导入 JPEG、PNG 与单图 TIFF，并统一导出为 JPEG 或无损 PNG

## 其他改进

照片卡片和预览会更一致地适应窗口可用宽度；Photo Size 可以统一调整主要工作页面中的预览尺寸，不影响来源照片或导出文件的像素尺寸。

界面支持英文与简体中文，并新增应用内更新检查。全部照片处理继续在本地完成，来源照片始终只读，已有目标文件不会被静默覆盖。

## 系统要求

- Apple Silicon Mac
- macOS 26.0 或更高版本

## 下载与安装

优先从 Assets 下载 `FramePair-0.3-macOS-arm64.dmg`。`FramePair-0.3-macOS-arm64.zip` 作为备用安装包提供；GitHub 自动生成的 Source code 压缩包不是可运行的应用。

完整安装步骤与功能说明见 [README](https://github.com/CedricChanning/FramePair#readme)。

## 完整性

`FramePair-0.3-macOS-arm64.dmg` 的 SHA-256：

```text
418e1331e48243608b169f685735fe61c977fa1f4ae86399c3321aa49d94599b
```

`FramePair-0.3-macOS-arm64.zip` 的 SHA-256：

```text
87f0a00d72fd5de1f3047c931a83b429a3aaf6a871c9f9485d0cd9d2c3de4ba1
```

FramePair 应用使用 Developer ID 签名并经过 Apple 公证，面向 Apple Silicon（arm64）Mac 分发。

安装或使用问题可以通过本仓库的 [Issues](https://github.com/CedricChanning/FramePair/issues) 反馈。

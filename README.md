<h1 align="center">FRAME · WN9</h1>
<p align="center">把更多光影与色彩选择，带进 GR II。</p>
<p align="center">
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN9.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wn9.svg" alt="WN9 · 当前版本" height="32"></a>
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN3.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wn3.svg" alt="WN3 · 历史版本" height="32"></a>
</p>
<p align="center"><a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/software.md">软件介绍</a> · <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/firmware/WN9.md">WN9 固件介绍</a> · <a href="#下载与开始">下载与开始</a></p>

## 下载与开始

**当前版本：WN9 固件 · FRAME App 1.0.3（103）**

| 下载 | 适用对象 | 内容 |
| :-- | :-- | :-- |
| **[WN9 相机固件](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.3/FRAME-GR2-WN9-Firmware.zip)** | RICOH GR II | 固件、更新说明与校验值；[原始固件文件](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.3/rg2_v003.frm) |
| **[FRAME for Android](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.3/FRAME-Android-1.0.3-103.apk)** | Android 8.0 及以上 | APK 安装包 |
| **[FRAME for macOS](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.3/FRAME-macOS-1.0.3-103-arm64.dmg)** | Apple Silicon · macOS 13 及以上 | 已公证 DMG，运行时内置 |
| **[FRAME for Windows](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.3/FRAME-Windows-1.0.3-103-Setup.exe)** | Windows 10/11 x64 | 安装版；[便携版](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.3/FRAME-Windows-x64-1.0.3-103.zip) |
| **FRAME for iPhone / iPad** | iOS / iPadOS 16 及以上 | TestFlight 准备中 |

[全部发布附件](https://github.com/Lyle-xub/FRAME-GR2/releases/tag/v1.0.3) · [SHA-256 校验清单](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.3/SHA256SUMS.txt) · [软件介绍](https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/software.md) · [WN9 固件介绍](https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/firmware/WN9.md)

> 固件适用于 RICOH GR II。首次安装 FRAME 前，请先更新到理光官方 3.00；更新时使用充满的电池，写入期间保持供电。

---

## WN9 相对 WN3 新增功能

### 🎞️ 色彩与光效

- **高光溢出与横向拉丝**：可搭配原生、负片和自定滤镜，并在颜色处理完成后叠加。
- **LUT17 模式**：自定滤镜可按 **DISP** 在原生拟合与 LUT17 之间切换。
- **V5 联合拟合**：配套 App 导入时可选择 WN3 拟合或 V5，支持暂停、继续与任务恢复。
- **CINESTILL 800T**：配套 App 新增预设，并提供可左右切换的多场景参考图。

### 🎛️ 音效与参数

- **音效编辑**：导入音频、波形裁切、微调与试听，可设置关机音效、对焦确认音和快门提示音，并调整启用状态与音量。
- **扩展参数调整**：「无」滤镜也可按 Fn2 进入参数页，原生、负片和自定滤镜按各自支持范围显示参数；滤镜强度与光效档位可分别调整。

### 🖼️ 构图与照片信息

- **更多画幅**：新增 XPan、自定义照片比例及独立 RAW 比例设置。
- **三槽自定水印**：支持 App 导入、预览与调整，并新增四向 GR 标识。
- **原生 DISP 信息面板**：回放时查看拍摄时的滤镜名称、图标与参数，支持 JPEG、RAW 和 RAW+。
- **扩展 RAW 编辑**：新增负片、自定滤镜及 HDF、颗粒、高光溢出和拉丝参数调整。

### 📲 传输与配套 App

- **SD 卡文件管理与固件上传**：支持中文等 Unicode 文件名及长文件名。
- **固件版本识别**：App 可读取固件名称并确认更新状态。
- **iPhone / iPad 支持**：新增 iOS 版本，与其他平台使用同一套滤镜与相机功能。

---

## 修复与优化

- **照片信息**：修复 RAW+ 一直显示 Loading、DISP 信息空白或闪烁，以及切换照片时短暂出现 Meta 提示的问题。
- **自定菜单与回放**：修复 OK 确认、上下选择不稳定，以及比例切换后画面位置异常和回放退出的问题。
- **启动流程**：优化参数恢复顺序，减少重复通知与画面重配置引起的开机异常。
- **拟合运行库**：修复导入末尾报错、运行库意外退出，以及取消、暂停或恢复时的任务与源文件状态问题。
- **文件与照片传输**：修复 SD 列表导致预览黑屏、响应长度缺失、上传取消与最终应答异常等问题，优化原图导出和文件上传速度。
- **水印与操作提示**：修复水印导入和 RAW 编辑参数链路，整理照片装饰布局，统一自动收回的浮层通知、进度与取消操作。

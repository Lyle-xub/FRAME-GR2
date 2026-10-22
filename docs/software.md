# FRAME 软件

<p align="center">
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WNX.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wnx.svg?v=wnx-20261022" alt="WNX · 当前版本" height="32"></a>
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN3.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wn3.svg?v=wnx-20261022" alt="WN3 · 历史版本" height="32"></a>
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN9.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wn9.svg?v=wnx-20261022" alt="WN9 · 历史测试版" height="32"></a>
</p>

**当前配套 WNX 固件与 App 1.0.4（104）。**

## 下载与开始

**当前配套：WNX 固件 · FRAME App 1.0.4（104）。** Android、Mac 和 Windows 安装包与本页版本对应；iOS 同版本已开启 TestFlight 内部测试。

| 平台 | 下载与版本 | 要求 |
| :-- | :-- | :-- |
| GR II 固件 | [WNX 固件包](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.4/FRAME-GR2-WNX-Firmware.zip) · [原始固件](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.4/rg2_v003.frm) | RICOH GR II |
| Android | [FRAME 1.0.4（104）APK](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.4/FRAME-Android-1.0.4-104.apk) | Android 8.0 及以上 |
| Mac · Apple Silicon | [FRAME 1.0.4（104）arm64 DMG](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.4/FRAME-macOS-1.0.4-104-arm64.dmg) | macOS 13 及以上 |
| Mac · Intel | [FRAME 1.0.4（104）x64 DMG](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.4/FRAME-macOS-1.0.4-104-x64.dmg) | macOS 13 及以上 |
| Windows | [FRAME 1.0.4（104）安装版](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.4/FRAME-Windows-1.0.4-104-Setup.exe) · [便携版](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.4/FRAME-Windows-x64-1.0.4-104.zip) | Windows 10/11 x64 |
| iPhone / iPad | **1.0.4（104）· TestFlight 内部测试已开启** | iOS / iPadOS 16 及以上，仅已获授权的内部测试成员 |

[全部发布附件](https://github.com/Lyle-xub/FRAME-GR2/releases/tag/v1.0.4) · [SHA-256 校验清单](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.4/SHA256SUMS.txt) · [软件介绍](https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/software.md) · [固件介绍](https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/firmware/WNX.md)

## WNX 相对 WN3 的新增功能

### 🎞️ 色彩与参数

- **高光溢出与横向拉丝**：配合原生、负片和自定滤镜，在颜色处理后叠加；HDF 与颗粒可分别调整。
- **原生拟合 / LUT17**：自定滤镜按 DISP 切换，底栏显示当前方式，OK 确认选用。
- **V5 联合拟合**：导入 CUBE / XMP 时可选择 WN3 原拟合或 V5，支持暂停、继续与恢复。
- **更多参数入口**：「无」、负片与自定滤镜有独立参数页；原生滤镜保留原生数值刻度与调整习惯。
- **预设与参考图**：内置 CINESTILL 800T，多场景参考图支持左右切换，也可使用自己的照片。

### 🖼️ 构图与照片信息

- **更多画幅**：XPan、自定义比例及独立 RAW 比例设置。
- **三槽自定水印**：App 可导入、预览与调整，并可选择 GR 标识和照片装饰。
- **原生 DISP 面板**：回放时查看拍摄当时的滤镜名称、图标与参数。
- **RAW 编辑扩展**：支持负片、自定滤镜及 HDF、颗粒与两项光效参数。

### 🔊 音效与关机素材

- **音效编辑**：导入、试听和裁剪关机音效、快门提示音与对焦确认音。
- **关机图片与动画**：预览、缩放、旋转、调整构图，并分别管理画面和声音。

### 📲 App 与传输

- **旧固件兼容**：基础连接和原图导出不依赖新扩展接口；各功能按实际固件能力开放。
- **原始 JPEG / DNG**：按日期浏览并导出原文件，保留原始字节。
- **SD 文件与固件上传**：支持中文等 Unicode 文件名、连续分片、取消和保存结果核对。
- **多平台**：Android、Apple Silicon Mac、Intel Mac、Windows、iPhone / iPad 使用一致的功能分组。
- **统一反馈**：浮层进度与结果提示，减少旧连接和后台任务对新操作的干扰。

---

## WN3 历史配套软件

**Android 0.65.3 · macOS 0.65.3 · Windows 0.66.1（78）**，与 [WN3 原发行版](https://github.com/Lyle-xub/FRAME-GR2/releases/tag/v0.62.1-wn3)保持一致。

| 平台 | 配套版本与下载 | 要求 |
| :-- | :-- | :-- |
| Android | [FRAME 0.65.3 APK](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v0.62.1-wn3/FRAME-Android-0.65.3.apk) | Android 8.0 及以上 |
| macOS | [FRAME 0.65.3 DMG](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v0.62.1-wn3/FRAME-macOS-0.65.3-arm64.dmg) | Apple Silicon · macOS 13 及以上 |
| Windows | [FRAME 0.66.1（78）安装程序](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v0.62.1-wn3/FRAME-Windows-WN3-0.66.1-78-Setup.exe) | Windows 10/11 x64 |

| 功能 | 可以完成的操作 |
| :-- | :-- |
| 滤镜管理 | 导入 CUBE、兼容 XMP 与项目 JSON，编辑名称、图标、配色和 Emoji，预览并管理 16 个机内滤镜位置。 |
| 色彩预览 | 使用自己的照片比较原图、LUT 原效果和参数预览。 |
| 关机素材 | 导入图片、GIF 和视频，缩放、旋转并调整构图。 |
| 关机音效 | 导入 WAV / MP3 / M4A 等音频，波形裁剪、0.01 秒微调、试听和重新编辑，上传片段最多 3 秒。 |
| 原图导出 | 按日期浏览相机照片，筛选 JPEG / RAW，单张或批量导出，保留原始文件内容。 |
| 无线传输 | 连接相机 Wi-Fi，导入滤镜和关机素材，查看传输进度。 |

Android 与 macOS 0.65.3 修复滤镜详情页导入无响应、确认窗口与页面切换问题，并将导入进度和结果提示移至滤镜位置列表上方。Windows 0.66.1（78）基于 WN3 / App 0.65.3，修复退出卡住，支持安装、升级和卸载并保留个人滤镜数据。

macOS 0.65.3 采用本地签名；首次打开如遇系统拦截，可在系统“隐私与安全性”中按提示允许该应用。

[WN3 固件与使用说明](https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN3.md) · [WN3 全部附件](https://github.com/Lyle-xub/FRAME-GR2/releases/tag/v0.62.1-wn3) · [固件与 App 校验清单](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v0.62.1-wn3/SHA256SUMS.txt)


[WN9 / App 1.0.3 历史测试资料](https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN9.md)

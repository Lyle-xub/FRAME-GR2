<h1 align="center">FRAME · WNX-L1</h1>
<p align="center">把喜欢的色彩、构图和声音，带进 GR II。</p>
<p align="center">
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WNX.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wnx.svg?v=wnx-l1-20261023" alt="WNX-L1 · 当前版本" height="32"></a>
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN3.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wn3.svg?v=wnx-l1-20261023" alt="WN3 · 历史版本" height="32"></a>
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN9.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wn9.svg?v=wnx-l1-20261023" alt="WN9 · 历史测试版" height="32"></a>
</p>

<p align="center"><b>WNX-L1 固件 · App 1.0.6</b></p>

## 下载与开始

**当前配套：WNX-L1 固件 · FRAME App 1.0.6（107），iOS 为 1.0.6（107）。** Android、Mac 和 Windows 安装包与本页版本对应；iOS 同版本已提交 TestFlight 公测审核，审核通过后开放。

| 平台 | 下载与版本 | 要求 |
| :-- | :-- | :-- |
| GR II 固件 | [WNX-L1 固件包](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.6/FRAME-GR2-WNX-L1-Firmware.zip) · [原始固件](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.6/rg2_v003.frm) | RICOH GR II |
| Android | [FRAME 1.0.6（107）APK](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.6/FRAME-Android-1.0.6-107.apk) | Android 8.0 及以上 |
| Mac · Apple Silicon | [FRAME 1.0.6（107）arm64 DMG](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.6/FRAME-macOS-1.0.6-107-arm64.dmg) | macOS 13 及以上 |
| Mac · Intel | [FRAME 1.0.6（107）x64 DMG](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.6/FRAME-macOS-1.0.6-107-x64.dmg) | macOS 13 及以上 |
| Windows | [FRAME 1.0.6（107）安装版](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.6/FRAME-Windows-1.0.6-107-Setup.exe) · [便携版](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.6/FRAME-Windows-x64-1.0.6-107.zip) | Windows 10/11 x64 |
| iPhone / iPad | [1.0.6（107）· TestFlight 公测入口](https://testflight.apple.com/join/UHu8JxZn) | iOS / iPadOS 16 及以上；107 正在等待 Apple 公测审核 |

[全部发布附件](https://github.com/Lyle-xub/FRAME-GR2/releases/tag/v1.0.6) · [SHA-256 校验清单](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.6/SHA256SUMS.txt) · [软件介绍](https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/software.md) · [固件介绍](https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/firmware/WNX.md)

---

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

## App 1.0.6 修复与优化

- 修复更换参考图后长期停在“正在保存滤镜”：保存只写入参考图选择和原图，色彩预览在独立队列中按需生成。
- 保存期间仍可滚动页面；预览显示进度，支持取消和重新生成，忽略取消后的旧结果。
- 待生成预览时先显示并标注参考原图；复用已有内置预览。缓存淘汰只清理派生图，不删除保存的原图。
- 支持最多 12 张参考图、逐张删除、全部删除后保存，以及失败回滚。
- 保留 Android 打包脚本路径修复，以及 iOS 文件系统对象生命周期、照片最终保存、关机图片／动画／视频导入、内置音效读取和功能页闪烁修复。

## 安装与使用

首次安装 FRAME 前，先按理光官方说明确认 GR II 已更新至官方 3.00；升级文件保持 `rg2_v003.frm` 文件名。具体步骤可查看 [WN3 历史页面中的正常更新教程](docs/versions/WN3.md#正常更新教程)，其中“FRAME 固件”请使用本页 WNX 文件。

Mac 两种架构的安装包均已签名、公证并包含运行库。Windows 便携版须完整解压后运行。iOS 1.0.6（107）已提交公测审核，审核通过后会自动开放并通知测试员。[加入 TestFlight 公测](https://testflight.apple.com/join/UHu8JxZn)。

## WNX-L1

这是稳定版

## 支持开发

如果 FRAME 让你的 GR II 多了一点想拍的理由，欢迎请我喝杯咖啡，支持后续开发与维护。

赞赏完全自愿。点一个 Star、分享你的作品或反馈使用体验，也同样是很好的支持。

<p align="center">
  <a href="https://github.com/Lyle-xub/FRAME-GR2/releases/download/v0.62.1-wn3/support-wechat.png">
    <img src="https://github.com/Lyle-xub/FRAME-GR2/releases/download/v0.62.1-wn3/support-wechat.png" alt="通过微信支付支持 FRAME 开发" width="300">
  </a>
  <a href="https://github.com/Lyle-xub/FRAME-GR2/releases/download/v0.62.1-wn3/support-alipay.png">
    <img src="https://github.com/Lyle-xub/FRAME-GR2/releases/download/v0.62.1-wn3/support-alipay.png" alt="通过支付宝支持 FRAME 开发" width="300">
  </a>
</p>
<p align="center"><sub>使用对应 App 扫码；也可点击图片保存后识别。感谢每一份支持。</sub></p>

## 历史版本

- [WN3 历史版本](docs/versions/WN3.md)：保留 Android / macOS 0.65.3、Windows 0.66.1（78）配套下载与原使用说明。
- [WN9 历史测试版](docs/versions/WN9.md)：保留 App 1.0.3（103）资料。

---

FRAME 为独立扩展项目，不代表理光官方发布。胶片与相机商标归各自权利人所有。

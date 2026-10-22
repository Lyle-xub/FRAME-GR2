<h1 align="center">FRAME · WNX-L1</h1>
<p align="center">把喜欢的色彩、构图和声音，带进 GR II。</p>
<p align="center">
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WNX.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wnx.svg?v=wnx-l1-20261023" alt="WNX-L1 · 当前版本" height="32"></a>
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN3.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wn3.svg?v=wnx-l1-20261023" alt="WN3 · 历史版本" height="32"></a>
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN9.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wn9.svg?v=wnx-l1-20261023" alt="WN9 · 历史测试版" height="32"></a>
</p>

<p align="center"><b>WNX-L1 固件 · App 1.0.5</b></p>

## 下载与开始

**当前配套：WNX-L1 固件 · FRAME App 1.0.5（105），iOS 为 1.0.5（106）。** Android、Mac 和 Windows 安装包与本页版本对应；iOS 同版本已开启 TestFlight 内部测试。

| 平台 | 下载与版本 | 要求 |
| :-- | :-- | :-- |
| GR II 固件 | [WNX-L1 固件包](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.5/FRAME-GR2-WNX-L1-Firmware.zip) · [原始固件](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.5/rg2_v003.frm) | RICOH GR II |
| Android | [FRAME 1.0.5（105）APK](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.5/FRAME-Android-1.0.5-105.apk) | Android 8.0 及以上 |
| Mac · Apple Silicon | [FRAME 1.0.5（105）arm64 DMG](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.5/FRAME-macOS-1.0.5-105-arm64.dmg) | macOS 13 及以上 |
| Mac · Intel | [FRAME 1.0.5（105）x64 DMG](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.5/FRAME-macOS-1.0.5-105-x64.dmg) | macOS 13 及以上 |
| Windows | [FRAME 1.0.5（105）安装版](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.5/FRAME-Windows-1.0.5-105-Setup.exe) · [便携版](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.5/FRAME-Windows-x64-1.0.5-105.zip) | Windows 10/11 x64 |
| iPhone / iPad | **1.0.5（106）· TestFlight 内部测试已开启** | iOS / iPadOS 16 及以上，仅已获授权的内部测试成员 |

[全部发布附件](https://github.com/Lyle-xub/FRAME-GR2/releases/tag/v1.0.5) · [SHA-256 校验清单](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.5/SHA256SUMS.txt) · [软件介绍](https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/software.md) · [固件介绍](https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/firmware/WNX.md)

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

## App 1.0.5 修复与优化

- 各端参考图支持添加、逐张删除、全部删除并保存；保留所选顺序，空列表不会自动恢复内置图。
- 修复 Android 打包环境中参考图处理脚本路径不可直接读取导致的保存失败。
- 修复 iOS 忙碌状态切换时 SD、水印、照片等功能页反复重建、闪烁和丢失读取状态。
- iOS 106 修复文件操作对象在后台任务结束后被释放，导致照片下载后保存失败，以及关机图片、动画、视频导入空指针的问题。
- iOS 导出失败时显示具体阶段与原因，并保留已接收数据量；未保存的照片不会被计为导出成功。
- 修复 iOS 参考图运行库初始化卡住；限制关机图片预览尺寸和重复传输，最终编码使用原始帧。
- 修复 iOS 内置 PCM WAV 音效读取，并补充可读错误和诊断信息。

## 安装与使用

首次安装 FRAME 前，先按理光官方说明确认 GR II 已更新至官方 3.00；升级文件保持 `rg2_v003.frm` 文件名。具体步骤可查看 [WN3 历史页面中的正常更新教程](https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN3.md#正常更新教程)，其中“FRAME 固件”请使用本页 WNX 文件。

Mac 两种架构的安装包均已签名、公证并包含运行库。Windows 便携版须完整解压后运行。iOS 1.0.5 本轮只安排内部测试，旧公开邀请链接不用于分发本轮构建。

## 已知问题

WNX-L1 优化早期加载器搬运与清零，但偶发额外镜头伸缩尚未取得实机修复确认。机内仍显示 WNX，单靠名称无法区分旧构建与 L1；请核对固件 SHA-256：`c8fb8602b92bc7e4727080b538e6530b45fdf527aeb385a1d41f97a3687dbdbe`。历史固件保留作回退。

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

- [WN3 历史版本](https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN3.md)：保留 Android / macOS 0.65.3、Windows 0.66.1（78）配套下载与原使用说明。
- [WN9 历史测试版](https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN9.md)：保留 App 1.0.3（103）资料。

---

FRAME 为独立扩展项目，不代表理光官方发布。胶片与相机商标归各自权利人所有。

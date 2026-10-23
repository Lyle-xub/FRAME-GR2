# FRAME · WNX-L1 固件

<p align="center">
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WNX.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wnx.svg?v=wnx-l1-20261023" alt="WNX-L1 · 当前版本" height="32"></a>
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN3.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wn3.svg?v=wnx-l1-20261023" alt="WN3 · 历史版本" height="32"></a>
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN9.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wn9.svg?v=wnx-l1-20261023" alt="WN9 · 历史测试版" height="32"></a>
</p>

**适用机型：RICOH GR II；配套软件：FRAME 1.0.6；各端构建 107。**

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

[WNX-L1 固件包](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.6/FRAME-GR2-WNX-L1-Firmware.zip) · [原始固件文件](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.6/rg2_v003.frm) · [校验清单](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.6/SHA256SUMS.txt)

## 安装与使用

首次安装 FRAME 前，先按理光官方说明确认 GR II 已更新至官方 3.00；升级文件保持 `rg2_v003.frm` 文件名。具体步骤可查看 [WN3 历史页面中的正常更新教程](https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN3.md#正常更新教程)，其中“FRAME 固件”请使用本页 WNX 文件。

Mac 两种架构的安装包均已签名、公证并包含运行库。Windows 便携版须完整解压后运行。iOS 1.0.6（107）已提交公测审核，审核通过后会自动开放并通知测试员。[加入 TestFlight 公测](https://testflight.apple.com/join/UHu8JxZn)。

## 已知问题

WNX-L1 优化早期加载器搬运与清零，但偶发额外镜头伸缩尚未取得实机修复确认。机内仍显示 WNX，单靠名称无法区分旧构建与 L1；请核对固件 SHA-256：`c8fb8602b92bc7e4727080b538e6530b45fdf527aeb385a1d41f97a3687dbdbe`。历史固件保留作回退。

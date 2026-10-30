# FRAME · WNX-L3 固件

<p align="center">
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WNX.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wnx.svg?v=WNX-L3-20261031" alt="WNX-L3 · 当前版本" height="32"></a>
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN3.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wn3.svg?v=WNX-L2-20261025" alt="WN3 · 历史版本" height="32"></a>
  <a href="https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN9.md"><img src="https://raw.githubusercontent.com/Lyle-xub/FRAME-GR2/main/docs/assets/version-wn9.svg?v=WNX-L2-20261025" alt="WN9 · 历史测试版" height="32"></a>
</p>

**适用机型：RICOH GR II；配套软件：FRAME 1.0.9（110）。iOS 110 先内测，公测保留 1.0.7（108）。**

## WNX-L3 新增功能与修复

这是稳定版。

- **机内滤镜管理**：通过 App 隐藏、恢复和排序原生滤镜；保留“自定”子菜单，主列表与自定列表分别排序。排序使用固定滤镜编号，参数、保存记录和导入槽位保持原有归属。
- **更多机内水印**：新增拍立得；相机外框采用上方外框、下方原图的拼接方式，适配自定比例。照片完整保留，外框屏幕按比例填充；极端比例补白，改善颜色边缘错位。
- **RAW 编辑与确认**：修复负片／自定滤镜预览和保存有时不生效、RAW 编辑后回放名称错误，以及内置水印按 OK 有时无响应。
- **处理速度**：合并 H1 高光溢出处理优化，复用水印缩放与编码缓冲；启动流程和预读量保持当前验证布局。
- **各端软件同步**：Android、Apple Silicon Mac、Intel Mac、Windows 更新至 FRAME 1.0.9（110），同步滤镜排序、隐藏／恢复及完整机内水印选项。iOS 1.0.9（110）先进行 TestFlight 内部测试；公开测试入口继续提供现有公测版本。

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

[WNX-L3 固件包](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.6/FRAME-GR2-WNX-L3-Firmware.zip) · [原始固件文件](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.6/rg2_v003.frm) · [校验清单](https://github.com/Lyle-xub/FRAME-GR2/releases/download/v1.0.6/SHA256SUMS.txt)

## 安装与使用

首次安装 FRAME 前，先按理光官方说明确认 GR II 已更新至官方 3.00；升级文件保持 `rg2_v003.frm` 文件名。具体步骤可查看 [WN3 历史页面中的正常更新教程](https://github.com/Lyle-xub/FRAME-GR2/blob/main/docs/versions/WN3.md#正常更新教程)，其中“FRAME 固件”请使用本页 WNX 文件。

Mac 两种架构的安装包均已签名、公证并包含运行库。Windows 便携版须完整解压后运行。iOS 1.0.9（110）先进行 TestFlight 内部测试；公开测试入口继续提供 1.0.7（108）。[加入 TestFlight 公测](https://testflight.apple.com/join/UHu8JxZn)。

## WNX-L2

这是稳定版

# Madrid2flip（小米 18 背屏移植模块）

面向 **Xiaomi MIX Flip 2 (`bixi`, HyperOS 4 / Android 17)** 的独立 Xposed 模块，将小米 18 (`madrid`) 背屏中心（动态壁纸、AI 应用卡、Lumi 语音陪伴、个性签名）完整移植到 MIX Flip 2 外屏运行。

## 主要功能

- 合盖拍两下指纹键全屏唤起小米 18 背屏，支持直接息屏直达 AOD / 回锁屏 / 回外屏桌面三档退出；
- 展开 / 半折桌钟自动拉起、轻敲背面快捷手势、控制中心快捷磁贴；
- 双摄挖孔对齐视口 + 实时 GPU 毛玻璃延展背板 + 零白屏平滑淡入动画；
- 独立后置光感自动亮度倍率与亮度上限、重力 `0°/180°` 旋转、左滑外屏自拍、防烧屏与倒扣息屏；
- 解锁主题商店背屏设置、AI 应用卡社区列表/下载与 Lumi 语音对话。

> **前置依赖**：需配合小米 18 背屏中心系统资源 KSU / Magisk 模块（`madrid_subscreen_port_v1.0.0.zip`）使用，请前往源码仓库 Releases 下载刷入：
> https://github.com/Aragamiz/Madrid2flip/releases
>
> 刷入资源模块并启用本 Xposed 模块（勾选默认推荐作用域）后，重启设备即可生效。

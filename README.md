# AstroDrop｜下载与使用

AstroDrop 是 Windows 和 Android 之间的局域网文件、文件夹与文字互传工具。配对后，可以拖放文件、发送剪贴板图片或文字，在会话中查看素材合集、传输状态与进度。无需云账号，局域网传输不经过云服务器。

## 下载

当前版本：**Windows 2.0.18 x64 / Android 2.0.22**。

- **[下载 Windows 安装版（推荐）](https://github.com/Pawaganti/AstroDrop-Downloads/releases/download/v2.0.18/AstroDrop-Windows-2.0.18-Setup.exe)**：运行中文安装向导，登记开始菜单与“已安装的应用”，支持覆盖安装和卸载，保留个人配置。
- **[下载 Windows 便携版](https://github.com/Pawaganti/AstroDrop-Downloads/releases/download/v2.0.18/AstroDrop-Windows-2.0.18-Portable.zip)**：Windows 10/11 x64，解压后双击 `AstroDrop.exe`；无需安装开发环境或 .NET。
- **[下载安卓 APK](https://github.com/Pawaganti/AstroDrop-Downloads/releases/download/v2.0.18/AstroDrop-Android-2.0.22.apk)**：Android 8.0及以上；更新时覆盖安装，不先卸载。
- [当前版本说明与校验文件](https://github.com/Pawaganti/AstroDrop-Downloads/releases/tag/v2.0.18)
- **[长期分享：最新版本下载页](https://github.com/Pawaganti/AstroDrop-Downloads/releases/latest)**

## 主要功能

- 输入六位配对码自动寻找同局域网设备，支持的扫码入口保留，已配对设备可重命名。
- 文件、整个文件夹、图片、视频、音频、压缩包、文档及纯文本互传；文字保留换行。
- Windows 支持拖放发送、粘贴图片、主窗口、快捷小窗、悬浮投递和托盘。
- 图片/视频缩略图、批量素材合集、传输进度；音频显示蓝色音符和实际格式。
- Android 支持分类浏览、搜索与排序、多选、预览、文件更新和后台接收。
- Windows 文件夹新增内容自动投递，默认关闭，可手动设置文件夹和接收设备。

同一Wi-Fi、热点或有线局域网应允许设备互访。访客网络隔离、防火墙或禁止局域网的VPN/TUN可能阻断连接。本版本不提供云中转；macOS不在本次下载范围内。

## 开始使用

1. Windows运行安装版EXE完成安装；或选便携版解压后双击 `AstroDrop.exe`。手机安装APK。
2. 两端接入可互通的局域网，在设备管理中显示/输入六位配对码完成配对。
3. 选择对方设备，拖入文件或通过手机添加文件后发送。

完整步骤、数据目录、升级和卸载说明见 [使用说明](使用说明.md)。本Windows便携版仍使用用户本机的应用数据目录，不随ZIP分发作者的设备身份和聊天记录。

## 当前版本视觉示例

下面是Windows2.0.18和Android2.0.22隔离测试生成的演示卡片，不是个人聊天或真实使用数据。

Windows音频卡片：

![Windows演示音频卡片](screenshots/windows-audio-demo.png)

Android音频卡片：

![Android演示音频卡片](screenshots/android-audio-demo.png)

## 关于本仓库

这里仅提供公开下载、使用说明和版本记录，不包含应用源码或内部开发资料。软件保留现有版权，未另行授予开源许可；第三方许可见运行包内的组件许可和[COPYRIGHT.md](COPYRIGHT.md)。

安装版使用相同的2.0.18应用程序，不修改现有便携包。安装版校验见发行附件 `SHA256SUMS-Setup.txt`；原 `SHA256SUMS.txt` 仍对应便携版和安卓包。升级或卸载安装版都保留配置、配对身份、记录和接收文件。

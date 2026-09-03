# 超级订阅

超级订阅是一个网盘转存工具，需要配合 [supersub.top](https://supersub.top) 资源站使用。

在电脑上登录你的网盘账号后，可以把选中的内容保存到自己的网盘，也可以订阅感兴趣的内容，在有新资源时自动转存。目前支持：

- 夸克网盘
- 阿里云盘
- 115 网盘

## 有哪些版本

### 桌面端

适合在 Windows 或 Mac 电脑上使用。打开软件后可以找资源、登录网盘、转存内容和查看任务。如果需要自动转存订阅更新，请保持程序运行。

### Docker 版

适合长时间运行在 NAS 或服务器上，可以在没有打开个人电脑的情况下持续处理转存任务。官方镜像：[`achievehf/supersub`](https://hub.docker.com/r/achievehf/supersub)。

### 微信小程序

小程序是附加的便捷管理入口，可以用来管理设备和网盘账号，也可以邀请好友把他们的网盘绑定到你的设备。

## 桌面端下载

当前正式版：[`v1.0.0`](https://github.com/AchieveHF/supersub/releases/tag/v1.0.0)

- [Windows x64 安装版（推荐）](https://github.com/AchieveHF/supersub/releases/download/v1.0.0/SuperSubscription-1.0.0-x64-setup.exe)：适合大多数 Windows 电脑，按提示安装后使用
- [Windows x64 便携版](https://github.com/AchieveHF/supersub/releases/download/v1.0.0/SuperSubscription-1.0.0-x64-portable.exe)：无需安装，下载后直接运行
- [macOS Apple 芯片版](https://github.com/AchieveHF/supersub/releases/download/v1.0.0/SuperSubscription-1.0.0-arm64.dmg)：适用于 M1、M2、M3、M4 等机型
- [macOS Intel 芯片版](https://github.com/AchieveHF/supersub/releases/download/v1.0.0/SuperSubscription-1.0.0-x64.dmg)：适用于 Intel 芯片的 Mac

GitHub 自动显示的 `Source code` 压缩包不是安装包，普通用户无需下载。

## 安全说明

网盘登录数据只保存在用户自己的设备本地。软件本身不提供或存储资源文件，请遵守所在地法律法规和网盘平台规则，只处理你有权使用的内容。

当前版本还没有通过 Windows 和 macOS 的官方签名认证，系统可能显示安全提示。请只从本仓库的 [Releases](https://github.com/AchieveHF/supersub/releases) 下载。

## 问题反馈

使用中遇到问题，可以通过本仓库的 [Issues](https://github.com/AchieveHF/supersub/issues) 反馈。请勿在公开页面上传网盘账号、登录信息、二维码或完整日志。

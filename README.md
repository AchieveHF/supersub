# 超级订阅

超级订阅支持夸克网盘、阿里云盘和 115 网盘的资源获取、转存及订阅自动转存。

本仓库是超级订阅的公开发行仓库，用于提供桌面安装包、Docker 部署文件、版本说明和校验文件；产品源码在私有仓库中维护，不在这里发布。

## 桌面端下载

当前桌面测试版：[`desktop-v0.1.0-beta.5`](https://github.com/AchieveHF/supersub/releases/tag/desktop-v0.1.0-beta.5)

- [Windows x64 安装版（exe）](https://github.com/AchieveHF/supersub/releases/download/desktop-v0.1.0-beta.5/SuperSubscription-0.1.0-beta.5-x64-setup.exe)
- [Windows x64 便携版（exe）](https://github.com/AchieveHF/supersub/releases/download/desktop-v0.1.0-beta.5/SuperSubscription-0.1.0-beta.5-x64-portable.exe)
- [macOS Apple Silicon（arm64.dmg）](https://github.com/AchieveHF/supersub/releases/download/desktop-v0.1.0-beta.5/SuperSubscription-0.1.0-beta.5-arm64.dmg)
- [macOS Intel（x64.dmg）](https://github.com/AchieveHF/supersub/releases/download/desktop-v0.1.0-beta.5/SuperSubscription-0.1.0-beta.5-x64.dmg)

桌面版本使用 `desktop-v*` 标签。请下载 Release 资产列表中明确标注平台的 `.exe` 或 `.dmg` 文件；GitHub 自动显示的 `Source code` 压缩包只包含本发行仓库的说明文件，并非应用源码或安装包。

## Docker

官方镜像发布在 Docker Hub：[`achievehf/supersub`](https://hub.docker.com/r/achievehf/supersub)。

Docker 版本使用 `v*` 标签。对应版本的 Compose 部署包、版本清单、SBOM 和校验文件会同时附在本仓库的 Release 中。

## 文件校验

每个 Release 都附带 `SHA256SUMS`。下载安装包或部署文件后，请先核对 SHA-256，再进行安装或升级。

## 问题反馈

普通使用问题可以通过本仓库的 Issues 反馈。涉及账号、凭据或其他敏感信息时，请勿发布到公开 Issue。

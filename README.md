# 超级订阅

超级订阅支持夸克网盘、阿里云盘和 115 网盘的资源获取、转存及订阅自动转存。

本仓库是超级订阅的公开发行仓库，用于提供桌面安装包、Docker 部署文件、版本说明和校验文件；产品源码在私有仓库中维护，不在这里发布。

## 桌面端下载

请前往 [Releases](https://github.com/AchieveHF/supersub/releases) 下载与系统匹配的安装包：

- Windows x64 安装版或便携版
- macOS Apple Silicon（arm64）
- macOS Intel（x64）

桌面版本使用 `desktop-v*` 标签。请下载 Release 资产列表中明确标注平台的 `.exe` 或 `.dmg` 文件；GitHub 自动显示的 `Source code` 压缩包只包含本发行仓库的说明文件，并非应用源码或安装包。

## Docker

官方镜像发布在 Docker Hub：[`achievehf/supersub`](https://hub.docker.com/r/achievehf/supersub)。

Docker 版本使用 `v*` 标签。对应版本的 Compose 部署包、版本清单、SBOM 和校验文件会同时附在本仓库的 Release 中。

## 文件校验

每个 Release 都附带 `SHA256SUMS`。下载安装包或部署文件后，请先核对 SHA-256，再进行安装或升级。

## 问题反馈

普通使用问题可以通过本仓库的 Issues 反馈。涉及账号、凭据或其他敏感信息时，请勿发布到公开 Issue。

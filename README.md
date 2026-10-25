# usework

usework 桌面应用的安装包与更新说明。本仓库用于公开分发，不包含应用项目源码。

## 下载

[查看最新版本](https://github.com/yangbo5207/usework-releases/releases/latest)

当前版本：**0.1.1**。

| 平台 | 安装包 |
| --- | --- |
| macOS · Apple Silicon（M 系列） | [下载 DMG](https://github.com/yangbo5207/usework-releases/releases/download/v0.1.1/usework-0.1.1-macos-arm64.dmg) |
| Windows 10 / 11 · x64 | [下载安装器](https://github.com/yangbo5207/usework-releases/releases/download/v0.1.1/usework-0.1.1-windows-x64-setup.exe) |

文件校验：[SHA256SUMS](https://github.com/yangbo5207/usework-releases/releases/download/v0.1.1/SHA256SUMS)。安装包直接从本仓库的 Releases 下载，不需要下载仓库 ZIP。

## 安装说明

macOS：打开 DMG，将 usework 拖到「应用程序」。当前版本仅支持 Apple Silicon，使用临时签名，未完成 Apple 公证。

Windows：运行安装器，安装到当前用户。电脑缺少 WebView2 时，安装器会联网安装所需运行时。当前 Windows 安装包未配置代码签名。

应用内置 Codex 0.163.0 完整运行时。运行用户项目所需的开发工具由用户自行准备；第三方组件许可证和说明随应用分发。

## 更新

版本说明见 [CHANGELOG](./CHANGELOG.md) 与 [Releases](https://github.com/yangbo5207/usework-releases/releases)。

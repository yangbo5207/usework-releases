# usework

usework 桌面应用的安装包与更新说明。本仓库用于公开分发，不包含应用项目源代码。

## 下载

[查看最新版本](https://github.com/yangbo5207/usework-releases/releases/latest)

| 平台 | 版本 | 安装包 |
| --- | --- | --- |
| macOS · Apple Silicon（M 系列） | 0.1.2 | [下载 DMG](https://github.com/yangbo5207/usework-releases/releases/download/v0.1.2/usework-0.1.2-macos-arm64.dmg) |
| Windows 10 / 11 · x64 | 0.1.1 | [下载安装器](https://github.com/yangbo5207/usework-releases/releases/download/v0.1.1/usework-0.1.1-windows-x64-setup.exe) |

本次仅更新 macOS，Windows 保留上一版本。[macOS 0.1.2 校验值](https://github.com/yangbo5207/usework-releases/releases/download/v0.1.2/SHA256SUMS) · [Windows 0.1.1 校验值](https://github.com/yangbo5207/usework-releases/releases/download/v0.1.1/SHA256SUMS)。安装包直接从 Releases 下载，无需下载仓库 ZIP。

## 自动更新

macOS 0.1.2 起包含整应用更新器。发现兼容新版后，左侧导航底部显示蓝色更新按钮，点击下载并选择安装重启。0.1.1 及更早版本需要先手动安装一次 0.1.2，后续更高版本才可在应用内升级。

`app.tar.gz`、`.sig` 和 `latest.json` 供应用更新器使用，无需手动解压。更新保留本机聊天、配置与邮箱数据；更新包使用数字签名校验。

## 安装说明

macOS：打开 DMG，将 usework 拖入“应用程序”。当前版本仅支持 Apple Silicon，使用临时代码签名，未完成 Apple 公证。

Windows：运行安装器，安装到当前用户。电脑缺少 WebView2 时，安装器会联网安装所需运行时。当前 Windows 安装包未配置代码签名。

应用内置 Codex 0.163.0 完整运行时。运行用户项目所需的开发工具仍由用户自行准备；第三方组件许可与说明随应用分发。

## 更新日志

版本说明见 [CHANGELOG](./CHANGELOG.md) 与 [Releases](https://github.com/yangbo5207/usework-releases/releases)。

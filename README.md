<div align="center">
  <img src="src-tauri/icons/128x128@2x.png" width="96" alt="mimi">
  <h1>Mimi</h1>
  <p>把电脑或麦克风声音转成实时翻译字幕。</p>
  <p>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/github/v/release/yuxino/mimi?style=flat&amp;logo=github&amp;logoColor=white" alt="最新版本"></a>
    <a href="https://github.com/yuxino/mimi/releases"><img src="https://img.shields.io/github/downloads/yuxino/mimi/total?style=flat&amp;labelColor=a85f82&amp;color=e889b5" alt="总下载量"></a>
    <a href="https://github.com/yuxino/mimi/actions/workflows/ci.yml?query=branch%3Amain"><img src="https://img.shields.io/github/actions/workflow/status/yuxino/mimi/ci.yml?style=flat&amp;logo=githubactions&amp;logoColor=white&amp;branch=main&amp;event=push&amp;label=CI" alt="main 分支 CI 状态"></a>
    <a href="LICENSE"><img src="https://img.shields.io/github/license/yuxino/mimi?style=flat&amp;logo=opensourceinitiative&amp;logoColor=white" alt="MIT 许可证"></a>
  </p>
  <p>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/badge/macOS-13%2B-555?style=flat&amp;logo=apple&amp;logoColor=white" alt="macOS 13+"></a>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/badge/Windows-x64-0078D4?style=flat&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0wIDBoMTF2MTFIMHptMTMgMGgxMXYxMUgxM3pNMCAxM2gxMXYxMUgwem0xMyAwaDExdjExSDEzeiIvPjwvc3ZnPg%3D%3D&amp;logoColor=white" alt="Windows x64"></a>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/badge/Linux-x86__64-FCC624?style=flat&amp;logo=linux&amp;logoColor=white" alt="Linux"></a>
    <a href="android/README.md"><img src="https://img.shields.io/badge/Android-app-3DDC84?style=flat&amp;logo=android&amp;logoColor=white" alt="Android"></a>
  </p>
  <p>
    <a href="README_EN.md"><strong>English</strong></a> · <a href="docs/readme/zh-CN.md">简体中文</a> · <a href="docs/readme/zh-TW.md">繁體中文</a> · <a href="docs/readme/ja.md">日本語</a> · <a href="docs/readme/th.md">ภาษาไทย</a> · <a href="docs/readme/ko.md">한국어</a> · <a href="docs/readme/fr.md">Français</a> · <a href="docs/readme/de.md">Deutsch</a>
  </p>
</div>

![Mimi 双语字幕示意：原创插画与示例对白](docs/assets/readme-preview.png)

字幕显示示意，使用示例对白。[看字幕与沉浸模式演示（旧版界面）](docs/demos/README.md)。

## 边听边看字幕

- **看懂正在播放的内容**：电影、直播、网课中的人声，显示为悬浮字幕。可看双语、只看译文或只看原文。
- **选择听什么**：默认听电脑声音，也可主动开启麦克风，或同时使用两路。macOS / Windows 11 可指定应用。
- **让字幕适合你**：调整位置、字号和颜色；沉浸模式只留字幕，点击穿透让你继续操作下方应用。
- **需要时再保存**：桌面端可保存字幕或录制所选音源，导出 TXT / WAV。默认不保存、不录音。

## 开始使用

1. **[下载 Mimi](https://github.com/yuxino/mimi/releases/latest)**。支持 macOS 13+（Apple 芯片 / Intel）、Windows x64、Linux x86_64；手机请看 [Android 安装与使用（英文）](android/README.md#start)。
2. **添加服务配置**。打开「设置 → 模型与服务」（旧版为「语音与翻译」），选择服务并保存凭证。不知道选哪家、Key 去哪拿？按[服务配置指南](docs/provider-setup.zh-CN.md#choose)操作。
3. **开启字幕**。选择音源、识别语言和翻译语言，播放内容，在「字幕」页开启「实时字幕」，按系统提示授予录音权限。

Mimi 免费，云服务可能收费。云端识别会接收音频，远程文字翻译会接收识别文字；本地处理需选择支持的 Apple 服务。具体要求见配置指南。

## 使用中遇到问题？

[使用指南](docs/usage.zh-CN.md)包含安装、权限、字幕显示和保存记录。没有字幕或连接失败，先看[识别错误](docs/usage.zh-CN.md#errors)；仍未解决可[反馈问题](https://github.com/yuxino/mimi/issues)。

## 贡献者

想帮 Mimi 改进？从[贡献指南（中英）](.github/CONTRIBUTING.md)开始。

感谢每一位写代码、提问题、试用和分享的朋友 (๑•̀ㅂ•́)و✧

特别感谢 [@yebuwudong](https://github.com/yebuwudong) 贡献 [Android 版](https://github.com/yuxino/mimi/pull/37)，以及 [@LLLin000](https://github.com/LLLin000) 贡献[字幕动效](https://github.com/yuxino/mimi/pull/67)和 [Windows 音源改进](https://github.com/yuxino/mimi/pull/89)。

也感谢 [@Chtholly000](https://github.com/Chtholly000) 改进 [Gemini 连续字幕和连接轮换](https://github.com/yuxino/Mimi/pull/176)。

感谢 [@EmmetZ](https://github.com/EmmetZ) 修复 [Wayland 下字幕浮窗与控制组件不同步移动的问题](https://github.com/yuxino/Mimi/pull/242)。

<p>
  <a href="https://github.com/yuxino"><img src="docs/assets/contributors/yuxino.svg" width="64" height="64" alt="@yuxino"></a>
  <a href="https://github.com/LLLin000"><img src="docs/assets/contributors/LLLin000.svg" width="64" height="64" alt="@LLLin000"></a>
  <a href="https://github.com/yebuwudong"><img src="docs/assets/contributors/yebuwudong.svg" width="64" height="64" alt="@yebuwudong"></a>
  <a href="https://github.com/Chtholly000"><img src="docs/assets/contributors/Chtholly000.svg" width="64" height="64" alt="@Chtholly000"></a>
  <a href="https://github.com/inhome"><img src="docs/assets/contributors/inhome.svg" width="64" height="64" alt="@inhome"></a>
  <a href="https://github.com/EmmetZ"><img src="docs/assets/contributors/EmmetZ.svg" width="64" height="64" alt="@EmmetZ"></a>
</p>

[查看所有贡献者](https://github.com/yuxino/mimi/graphs/contributors)

## 社区致谢

也感谢 [V2EX](https://www.v2ex.com/)、[LINUX DO](https://linux.do/)、[小众软件](https://meta.appinn.net/)、[NodeLoc](https://www.nodeloc.com/)、[Solo](https://solo.xin/)、[新趣集](https://xinquji.com/posts/859305)和[电鸭](https://eleduck.com/)社区朋友的试用、反馈与分享。

[MIT](LICENSE) © 2026 yuxino

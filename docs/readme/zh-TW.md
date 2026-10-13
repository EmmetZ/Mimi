<div align="center">
  <img src="../../src-tauri/icons/128x128@2x.png" width="96" alt="mimi">
  <h1>Mimi</h1>
  <p>系統聲音或麥克風即時字幕與翻譯，支援 Apple 晶片和 Intel Mac（macOS 13+），以及 Windows / Linux x86_64。</p>
  <p>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/github/v/release/yuxino/mimi?style=flat&amp;logo=github&amp;logoColor=white" alt="最新版本"></a>
    <a href="https://github.com/yuxino/mimi/releases"><img src="https://img.shields.io/github/downloads/yuxino/mimi/total?style=flat&amp;labelColor=a85f82&amp;color=e889b5" alt="總下載量"></a>
    <a href="https://github.com/yuxino/mimi/actions/workflows/ci.yml?query=branch%3Amain"><img src="https://img.shields.io/github/actions/workflow/status/yuxino/mimi/ci.yml?style=flat&amp;logo=githubactions&amp;logoColor=white&amp;branch=main&amp;event=push&amp;label=CI" alt="main 分支 CI 狀態"></a>
    <a href="../../LICENSE"><img src="https://img.shields.io/github/license/yuxino/mimi?style=flat&amp;logo=opensourceinitiative&amp;logoColor=white" alt="MIT 授權條款"></a>
  </p>
  <p>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/badge/macOS-13%2B-555?style=flat&amp;logo=apple&amp;logoColor=white" alt="macOS 13+"></a>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/badge/Windows-x64-0078D4?style=flat&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0wIDBoMTF2MTFIMHptMTMgMGgxMXYxMUgxM3pNMCAxM2gxMXYxMUgwem0xMyAwaDExdjExSDEzeiIvPjwvc3ZnPg%3D%3D&amp;logoColor=white" alt="Windows x64"></a>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/badge/Linux-x86__64-FCC624?style=flat&amp;logo=linux&amp;logoColor=white" alt="Linux"></a>
    <a href="../../android/README.md"><img src="https://img.shields.io/badge/Android-app-3DDC84?style=flat&amp;logo=android&amp;logoColor=white" alt="Android"></a>
  </p>
  <p>
    <a href="../../README_EN.md">English</a> · <a href="../../README.md">简体中文</a> · <a href="zh-TW.md">繁體中文</a> · <a href="ja.md">日本語</a> · <a href="th.md">ภาษาไทย</a> · <a href="ko.md">한국어</a> · <a href="fr.md">Français</a> · <a href="de.md">Deutsch</a>
  </p>
</div>

![Mimi 雙語字幕示意：原創插畫與範例對白](../assets/readme-preview.png)

字幕顯示示意，使用範例對白。[觀看字幕與沉浸模式示範（舊版介面）](../demos/README.md)。

## 邊聽邊看字幕

- **看懂正在播放的內容**：電影、直播、線上課程中的人聲，顯示為懸浮字幕。可看雙語、只看譯文或只看原文。
- **選擇聽什麼**：預設使用電腦聲音，也可主動開啟麥克風，或同時使用兩路。macOS / Windows 11 可指定應用程式。
- **讓字幕適合你**：調整位置、字級和顏色；沉浸模式只留字幕，點擊穿透讓你繼續操作下方應用程式。
- **需要時再儲存**：桌面版可儲存字幕或錄製所選音源，匯出 TXT / WAV。預設不儲存、不錄音。

## 開始使用

1. **[下載 Mimi](https://github.com/yuxino/mimi/releases/latest)**。支援 macOS 13+（Apple 晶片 / Intel）、Windows x64、Linux x86_64；手機請看 [Android 安裝與使用（英文）](../../android/README.md#start)。
2. **新增服務設定**。開啟「設定 → 模型與服務」（舊版為「語音與翻譯」），選擇服務並儲存認證資訊。不知道選哪家、Key 去哪拿？請看[服務設定指南（簡體中文）](../provider-setup.zh-CN.md#choose)。
3. **開啟字幕**。選擇音源、辨識語言和翻譯語言，播放內容，在「字幕」頁開啟「即時字幕」，依系統提示授予錄音權限。

Mimi 免費，雲端服務可能收費。雲端辨識會接收音訊，遠端文字翻譯會接收辨識文字；本機處理需選擇支援的 Apple 服務。需求詳見設定指南。

## 使用中遇到問題？

[使用指南](../usage.zh-TW.md)包含安裝、權限、字幕顯示和儲存記錄。沒有字幕或連線失敗，先看[辨識錯誤](../usage.zh-TW.md#errors)；仍未解決可[回報問題](https://github.com/yuxino/mimi/issues)。

## 貢獻者

想幫 Mimi 改進？從[貢獻指南（中英）](../../.github/CONTRIBUTING.md)開始。

感謝每一位寫程式碼、提問題、試用和分享的朋友 (๑•̀ㅂ•́)و✧

特別感謝 [@yebuwudong](https://github.com/yebuwudong) 貢獻 [Android 版](https://github.com/yuxino/mimi/pull/37)，以及 [@LLLin000](https://github.com/LLLin000) 貢獻[字幕動畫](https://github.com/yuxino/mimi/pull/67)和 [Windows 音訊來源改進](https://github.com/yuxino/mimi/pull/89)。

也感謝 [@Chtholly000](https://github.com/Chtholly000) 改進 [Gemini 連續字幕和連線輪換](https://github.com/yuxino/Mimi/pull/176)。

感謝 [@EmmetZ](https://github.com/EmmetZ) 修復 [Wayland 下字幕浮窗與控制元件未同步移動的問題](https://github.com/yuxino/Mimi/pull/242)。

感謝 [@wangmian0](https://github.com/wangmian0) 為 [DeepSeek 即時字幕翻譯關閉思考模式](https://github.com/yuxino/Mimi/pull/270)。

<p>
  <a href="https://github.com/yuxino"><img src="../assets/contributors/yuxino.svg" width="64" height="64" alt="@yuxino"></a>
  <a href="https://github.com/LLLin000"><img src="../assets/contributors/LLLin000.svg" width="64" height="64" alt="@LLLin000"></a>
  <a href="https://github.com/yebuwudong"><img src="../assets/contributors/yebuwudong.svg" width="64" height="64" alt="@yebuwudong"></a>
  <a href="https://github.com/Chtholly000"><img src="../assets/contributors/Chtholly000.svg" width="64" height="64" alt="@Chtholly000"></a>
  <a href="https://github.com/inhome"><img src="../assets/contributors/inhome.svg" width="64" height="64" alt="@inhome"></a>
  <a href="https://github.com/EmmetZ"><img src="../assets/contributors/EmmetZ.svg" width="64" height="64" alt="@EmmetZ"></a>
  <a href="https://github.com/wangmian0"><img src="../assets/contributors/wangmian0.svg" width="64" height="64" alt="@wangmian0"></a>
</p>

[檢視所有貢獻者](https://github.com/yuxino/mimi/graphs/contributors)

## 社群致謝

也感謝 [V2EX](https://www.v2ex.com/)、[LINUX DO](https://linux.do/)、[小眾軟體](https://meta.appinn.net/)、[NodeLoc](https://www.nodeloc.com/)、[Solo](https://solo.xin/)、[新趣集](https://xinquji.com/posts/859305)和[電鴨](https://eleduck.com/)社群朋友的試用、意見回饋與分享。

[MIT](../../LICENSE) © 2026 yuxino

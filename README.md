# 🖥️ Multi-Screen Screenshot and Blackout Tool / 多屏截图与黑屏工具 / マルチスクリーンキャプチャー＆ブラックアウトツール

A lightweight Windows tool for capturing a specific screen, blacking out others, and pasting screenshots into messaging apps like WeChat and QQ.  
轻量级 Windows 工具，可捕获指定屏幕截图，控制其他屏幕黑屏，并自动粘贴到 QQ、微信等聊天窗口。  
Windows向けの軽量ツール。指定した画面をキャプチャし、他の画面をブラックアウトし、WeChatやQQなどに自動貼り付けできます。

---

## 🌐 Language | 语言 | 言語

- [English](#-english)
- [简体中文](#-简体中文)
- [日本語](#-日本語)

---

## 📘 English

### Features

- `INS`: Capture screen 1 and paste into WeChat, QQ, or "Tencent Yuanbao".
- `HOME`: Toggle blackout on screen 2.
- `END`: Exit the program and remove blackout window.
- `CTRL+ALT+P`: Force reset (used when things get stuck).
- Esc exits the black screen manually.
- Hidden console, low-priority background process, and single-instance locking.
- Intelligent chat window detection and screenshot pasting automation.
- Activity logs stored at `%TEMP%\screen_log.txt`.

### Requirements

- Windows 10/11
- Visual Studio (C++ build)
- Admin privileges may be required for full keyboard/mouse control

### Installation & Run

```bash
git clone https://github.com/yourusername/screen-blackout-tool.git
cd screen-blackout-tool
build with Visual Studio
run the EXE

# 英语实时字幕：离线 Android 试用版

[下载安装包](https://github.com/whilolf-tech/snake-tetris-game/raw/refs/heads/downloads/english-live-1.2-offline/english-live-offline.apk)

Android 8.0 及以上。内置 Vosk 英语识别引擎和模型，无需系统语音服务或联网。首次打开等待模型初始化，再允许麦克风权限并点击开始。

这是调试签名试用包。构建、3 项单元测试、静态检查和宿主机英语音频识别测试已通过；尚未在 Android 真机上验证。识别可能受噪声、口音、人名和数字影响。

本分支仅用于安装包下载，不改动 main。校验值见 SHA256SUMS。APK 内含模型原始说明和第三方许可证（assets/licenses 和 assets/model-en-us/README）。

## 1.2 更新

修复每次字幕更新都强制滚到底部的问题：仅在底部跟随新字幕；手动向上查看、触摸或选择文字时不强制跳转。

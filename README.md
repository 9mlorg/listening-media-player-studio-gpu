# Listening Media Player Studio — GPU 文字起こしプログラム

Listening Media Player Studio が、文字起こしの画面で「GPU」を選んだときに使う補助プログラム（whisper-gpu）の配布場所です。

- アプリが必要なときに自動でダウンロードして使います。手動でダウンロードする必要はありません。
- 対象: Windows 64bit、NVIDIA / AMD の独立した GPU（Vulkan 対応ドライバー）
- アプリはダウンロード後に SHA-256 を確かめてから使います。値は各リリースに書いてあります。
- 中身: [whisper.cpp](https://github.com/ggml-org/whisper.cpp)（MIT ライセンス）を whisper-rs 経由で Vulkan 有効にしてビルドしたものです。

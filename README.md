# split-typing-trainer

A single-file, offline typing trainer for split & columnar keyboards.
Load your own Vial `.vil` layout, sync layers live over WebHID, and get
per-key / per-finger analytics so you can find and fix your weak spots.

分割・カラムスタッガ配列のキーボード向けの、単一HTMLで動くタイピング練習ソフトです。
Vialの `.vil` プロファイルを読み込んで自分の配列で練習でき、WebHIDで実機のレイヤーと
連動、キー別・指別の分析で弱点を可視化します。

## Features / 機能

- **Runs anywhere** — one self-contained `typing_trainer.html`, no install, works offline
- **Your layout** — import a Vial `.vil` profile; the on-screen keyboard reflects it
- **Live layer sync (WebHID)** — hold `MO` on the real keyboard to switch the displayed layer (Chrome/Edge; keyboard must be unlocked in Vial)
- **Practice modes** — position, random, English words, romaji (Japanese), weakness drill, free text, per-layer
- **Analytics** — most-mistyped keys, slowest keys, slow key-pairs (bigrams), per-finger stats, keyboard heatmap
- **Progress** — WPM, accuracy, speed history graph
- **Backup** — export / import all stats & settings as JSON (stored in your browser's localStorage)

## Usage / 使い方

Open `typing_trainer.html` in a browser (Chrome/Edge recommended for WebHID).
To sync layers with real hardware, close any other tab using the keyboard
(e.g. vial.rocks), click **⚡ 実機と連動**, and unlock the keyboard when prompted.

`typing_trainer.html` をブラウザで開くだけです（WebHID連動はChrome/Edge推奨）。
実機連動を使うときは、キーボードを掴んでいる他タブ（vial.rocks等）を閉じてから
「⚡ 実機と連動」を押し、案内に従ってアンロックしてください。

## Try it / 試す
▶ https://skymy-workshop.github.io/split-typing-trainer/

## Credits / 謝辞

Based on the mechanics of **美佳のタイプトレーナ (Mika Type Trainer)** by
**今村二朗 (Jiro Imamura)**.
Original: https://github.com/MIKATYPE/MIKATYPE_JAVA

See the [NOTICE](NOTICE) file for the original copyright and permission.

## License / ライセンス

New code in this repository is released under the [MIT License](LICENSE).
The original work remains under its author's terms (see NOTICE).

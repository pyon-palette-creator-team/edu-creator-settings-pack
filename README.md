# 教育版クリエイター機能表示パック（Education Edition Creator Settings Pack）

Minecraft Education（教育版）で、統合版と同じ設定の「クリエイター」の欄を使えるようにするリソースパックです。教育版で教材やアドオンを作る人向けの、開発用のパックです。

[English](#english)

> これは個人が作った非公式のパックです。Mojang Studios・Microsoft とは関係ありません。

## できること

教育版では、設定の「クリエイター」の欄が隠されています。このパックを有効にすると、設定の左の一覧に「クリエイター」が出て、次の設定が使えます。

- コンテンツログ（ログをファイルに書く、画面に出す、ログの細かさ、**ログの履歴の画面**、ログの削除）
- スクリプトデバッガー（パスコード、自動で接続、ホスト・ポート）
- スクリプトのウォッチドッグ（止まった・重いときの警告）
- 診断、座標のコピー、デバイスの情報（メモリの段階）、文字のフィルターのデバッグ

欄の中身は、教育版のゲームにもともと入っているものです。このパックは、隠している設定を外すだけで、ゲームの動きは変えません。

## 入れ方

1. [Releases](../../releases) から、いちばん新しい `.mcaddon` をダウンロードします
2. ファイルを開くと、Minecraft Education に取り込まれます
   - 統合版の Minecraft も入っている PC で統合版が開いたときは、ファイルを右クリック →「プログラムから開く」→ Minecraft Education を選びます
3. 教育版の「設定」→「グローバルリソース」で、このパックを有効にします
   - ワールドのリソースパックに入れるだけだと、ワールドの中で開いた設定の画面にしか効きません
4. 設定の左の一覧に「クリエイター」が出ます。出ないときは、ゲームを開き直します

確かめた版: Minecraft Education 1.26.33（Windows）

## 注意

- 開発用のパックです。生徒に配る教材のワールドには入れないでください
- 教育版の更新で設定の画面が変わると、表示がくずれたり、出なくなったりすることがあります

## ライセンス

[MIT](LICENSE)

---

## English

A resource pack that shows the "Creator" settings section in Minecraft Education, the same as in Minecraft Bedrock Edition. It is meant for people who make lessons and add-ons for Education Edition.

> This is an unofficial pack made by an individual. It is not affiliated with Mojang Studios or Microsoft.

### Features

Education Edition hides the "Creator" section in Settings. With this pack enabled, "Creator" appears in the settings list, with:

- Content Log (log to file, show on screen, log level, **content log history screen**, delete logs)
- Script Debugger (passcode, auto attach, host and port)
- Script Watchdog
- Diagnostics, copy coordinates, device info (memory tier), text filtering debug

These settings are already in the game. The pack only removes the UI rules that hide them.

### Install

1. Download the latest `.mcaddon` from [Releases](../../releases)
2. Open the file to import it into Minecraft Education
   - If Minecraft Bedrock Edition opens instead, right-click the file, choose "Open with", then Minecraft Education
3. In Education Edition, enable the pack in Settings > Global Resources
4. "Creator" appears in the settings list. If not, restart the game

Tested on: Minecraft Education 1.26.33 (Windows)

### Notes

- This is a pack for development. Do not include it in lesson worlds for students
- Game updates may change the settings screen and break this pack

### License

[MIT](LICENSE)


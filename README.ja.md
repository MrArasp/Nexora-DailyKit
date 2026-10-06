# NEXORA DAILYKIT

> Windows 10 / Windows 11 向けの軽量なデスクトップカレンダー＆デイリープランニングアプリです。

**Version:** 1.0.0 — Stable Release

[🇬🇧 English](README.md) · [🇮🇷 فارسی](README.fa.md) · [🇨🇳 简体中文](README.zh-CN.md) · [🇯🇵 日本語](README.ja.md) · [🇰🇷 한국어](README.ko.md) · [🇩🇪 Deutsch](README.de.md) · [🇫🇷 Français](README.fr.md) · [🇷🇺 Русский](README.ru.md)

---

## 概要

NEXORA DAILYKIT は、カレンダー、毎日の予定、タスク、Journal、リマインダー、日付情報を1つにまとめるローカル Windows アプリです。UI は現在 English と Persian のみです。

---

## 主な機能

- Gregorian / Persian-Jalali / Islamic
- デイリー情報、Tasks、Journal
- Windows通知とカスタムリマインダー音
- Desktop Layer ウィジェットと透明度
- System Tray
- ライト/ダーク/システムテーマ
- 機能別カラーと表示設定
- 自動/手動バックアップと復元
- English/Persian、LTR/RTL
- ローカル保存と About Us

---

## システム要件

- Windows 10 または Windows 11
- アプリをインストール/実行できる Windows ユーザーアカウント
- 通常のカレンダー、タスク、Journal、リマインダー、バックアップにインターネットは不要

---

## ダウンロード

公開 GitHub リポジトリの **Releases** から公式 Windows 版をダウンロードしてください。ソースコードは別管理です。


---

## インストール

1. Releases から最新の Windows インストーラーを取得。
2. インストーラーを実行。
3. Windows の手順を完了。
4. **NEXORA DAILYKIT** を起動。
5. 初回は English と Gregorian。
6. Settings で変更。


---

# 📖 完全ユーザーガイド

## 1. 初回起動

初期状態は英語、グレゴリオ暦、画面左下のタスクバー上部付近にあるウィジェット、既定の透明度、ローカル保存です。

<img width="358" height="531" alt="image" src="https://github.com/user-attachments/assets/d24eec7c-775d-419b-94d8-9d9869aca37b" />

## 2. メイン画面

**Calendar** は日付と月を表示します。**Settings** は外観、カレンダー、ウィジェット、リマインダー、バックアップ、言語を管理します。**About Us** は NEXORA 情報、リンク、寄付、ウォレットコピーを表示します。アプリ名は常に **NEXORA DAILYKIT** です。


## 3. カレンダー

月移動、日付選択、Today、主カレンダー変更、追加カレンダー表示、選択日の情報表示ができます。選択日は強く表示され、別の日を選ぶと今日の強調は弱くなります。

<img width="350" height="422" alt="image" src="https://github.com/user-attachments/assets/331a47a0-317c-44a9-9193-5c1d6e8b3539" />

## 4. カレンダーシステム

**Gregorian:** 国際標準カレンダー。 **Persian / Jalali:** ペルシャ太陽ヒジュラ暦。 **Islamic:** イスラム Hijri 暦。Islamic は Umm al-Qura ベースで、地域の月観測暦とは約1日異なる場合があります。Jalali はサポートされる天文学的 Solar Hijri 計算を使用します。


## 5. カレンダー表示設定

**Settings → Calendar** では主/第2/第3カレンダー、日付形式、数字形式、週の開始日を設定できます。週の開始日は自動、土曜、日曜、月曜。ペルシャ語UIでも日付数字は西洋/英語数字です。

<img width="579" height="500" alt="image" src="https://github.com/user-attachments/assets/c44bb4e3-93ad-4bcf-b09a-ce0175511d26" />

## 6. デイリー情報

日付を選択すると Daily Information が表示されます。**Tasks** は実行項目、**Journal** はその日の自由なメモです。

<img width="410" height="552" alt="image" src="https://github.com/user-attachments/assets/eec814e7-7e43-4bed-b03d-9f966a5c900f" />

## 7. タスク

タイトル、任意の説明、任意の時刻、完了状態を設定できます。作成、編集、完了、再開、削除が可能です。日付を選択 → Daily Information → **New Task** → 内容入力 → 保存。時刻を設定したタスクはリマインダーで通知できます。

<img width="1048" height="536" alt="image" src="https://github.com/user-attachments/assets/2ca3ac7f-02c3-42dd-b87b-4d9de9df2fc7" />

## 8. Journal

Journal は日付ごとのメモ用です。自動保存と手動保存を利用できます。日記、アイデア、個人記録、会議メモなどに使用できます。

<img width="410" height="552" alt="Screenshot 2026-10-04 101850" src="https://github.com/user-attachments/assets/692c451e-c953-4f0a-bad7-d532b3a86702" />

## 9. リマインダー

タスクに時刻を設定できます。期限になると Windows 通知、設定したサウンド、Snooze、Dismiss を利用できます。予定済みリマインダーは起動時に再読み込みされます。Windows の通知設定と権限も影響します。

<img width="333" height="112" alt="image" src="https://github.com/user-attachments/assets/0b2f412e-a355-4333-8326-ced3b3b5eac4" />

## 10. リマインダー設定

**Settings → Reminders** でサウンド、標準/カスタムサウンド、Test、Stop Sound、音量、標準 Snooze を設定できます。

<img width="500" height="386" alt="image" src="https://github.com/user-attachments/assets/8ecf51cb-a5d8-439d-9e1e-0b2d8992845e" />

## 11. デスクトップウィジェット

既定では画面左下、タスクバー上部。移動、サイズ変更、表示/非表示、Windows 起動時表示、Tray へ閉じる、位置リセットが可能です。Desktop Layer は**通常のウィンドウの背後**にあり、Always-on-top ではありません。マルチモニター位置復旧にも対応します。

<img width="338" height="468" alt="image" src="https://github.com/user-attachments/assets/9c100d8e-67d1-429e-a5c3-21a29539de95" />

## 12. ウィジェット透明度

20%〜100%。カレンダー操作中は一時的に100%表示になり、終了後に設定値へ戻ります。保存値は変更されません。

<img width="465" height="396" alt="image" src="https://github.com/user-attachments/assets/42a722d7-deb0-4d90-8ecf-f3638f155878" />

## 13. システムトレイ

ウィジェットを閉じても通常はアプリは終了しません。Tray から表示、非表示、**Exit** ができます。完全終了は Exit のみです。


## 14. 設定

トップの **Settings** から Appearance、Calendar、Widget、Reminders、Backup、Language、About を管理します。

<img width="475" height="186" alt="image" src="https://github.com/user-attachments/assets/acce7aae-c014-47f0-856e-503d5d769125" />

## 15. 外観

**Settings → Appearance** でテーマ、アクセント色、Calendar/Task/Journal/Reminder 色、背景、文字色、フォントサイズ、密度を設定できます。ライト、ダーク、システムテーマ、Preview、Reset に対応します。

<img width="642" height="845" alt="image" src="https://github.com/user-attachments/assets/5cd9dd94-a1a1-4f4e-839a-3b3499ff0ef2" />

## 16. 言語

**Settings → Language**。現在のUIは English と Persian。初回は English。ペルシャ語では必要な部分がRTL、URLとウォレットはLTRです。READMEの8言語はアプリUIの8言語対応を意味しません。

<img width="387" height="287" alt="image" src="https://github.com/user-attachments/assets/3a06df42-d5b1-4b17-be06-773b67f7facf" />

## 17. バックアップと復元

**Settings → Backup** で自動バックアップ、頻度、場所、保持、手動バックアップ、Restore を設定します。頻度は Daily、Weekly、On exit。既定場所は `Documents/Nexora DailyKit/Backups`。Open Folder は現在の保存場所、Backup Now は即時バックアップです。

<img width="579" height="454" alt="image" src="https://github.com/user-attachments/assets/75d613b9-06b0-4175-8db9-08d7f079d80c" />

## 18. 復元

復元前に現在のデータの安全バックアップが作成されます。Settings → Backup → Restore → バックアップ選択 → 確認 → 完了まで待つ。必要なら再起動/更新。復元中は終了しないでください。


## 19. About Us

公式リンク: Telegram https://t.me/nexora_labs_2026、GitHub https://github.com/MrArasp、Donations https://donito.me/nexora_labs。Network: EVM / USDT BEP20。Wallet: `0x5Bcdef9E0d9030e5cAa73e1D50aC71257EC8304e`。ウォレットはコピー用です。


## 20. データ保存とプライバシー

カレンダー、タスク、Journal、リマインダー、設定、バックアップはPCにローカル保存されます。NEXORAアカウント、クラウド、サブスクリプション、オンライン同期は通常不要です。外部リンクを意図的に開く場合のみインターネットを使用します。ローカルデータの安全性は Windows アカウントと保存フォルダにも依存します。


## 21. トラブルシューティング

ウィジェットが消えたら System Tray を確認。位置が違えば Settings → Widget → Reset Position。リマインダーが出なければタスク時刻、保存状態、アプリ/Tray、Windows通知、Reminder設定を確認。音が出なければ Windows/Reminder 音量と選択サウンドを確認し Test Sound。バックアップ場所は Settings → Backup → Open Folder。ペルシャ語は Language → Persian。Islamic の1日差は計算方式の違いで発生する場合があります。


## 22. カレンダー技術メモ

Jalali はサポートされる天文学的 Solar Hijri 計算、Islamic は Umm al-Qura データを使用します。Islamic は地域の月観測暦ではないため、他の暦と約1日異なる場合があります。


## 23. バージョン

**NEXORA DAILYKIT 1.0.0**。この文書は安定版1.0.0用です。最新のインストーラーと Release Notes は公開リポジトリを確認してください。


---

## フィードバック

- Telegram: https://t.me/nexora_labs_2026
- GitHub: https://github.com/MrArasp
問題報告にはバージョンと具体的な説明を記載してください。

## NEXORA を支援

https://donito.me/nexora_labs

**EVM / USDT BEP20**

`0x5Bcdef9E0d9030e5cAa73e1D50aC71257EC8304e`

## Copyright

© NEXORA. All rights reserved.
NEXORA DAILYKIT は Windows デスクトップアプリとして提供されます。リリースとライセンス情報は公開リポジトリと Release パッケージを確認してください。

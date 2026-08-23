# Rise and Shine Apps Webサイト (GitHub Pages)

Rise and Shine Appsのアプリ紹介およびポータルサイトのGitHub Pages用リポジトリです。

## 🌐 サイト構成・ページ一覧

- **[index.html](index.html)**: ポータル・アプリ一覧トップページ
- **[mojimon-master.html](mojimon-master.html)**: 『モジモンマスター』紹介ページ（iOSアプリ）
- **[tap-series.html](tap-series.html)**: 『タップシリーズ』紹介ページ（Androidアプリ：ひらがなタップ、漢字アタック、Word Rush）
- **[support.html](support.html)**: モジモンマスター サポート・FAQページ
- **[privacy.html](privacy.html)**: プライバシーポリシー案内ページ（外部ポリシーへリダイレクト）
- **[style.css](style.css)**: サイト全体の共通スタイルシート
- **[app-ads.txt](app-ads.txt)**: アプリ広告配信用の認証ファイル

## 📁 ディレクトリ構造

```text
mojimon_site/
├── assets/                  # 画像アセット
│   ├── aniki.png            # ポータル用キャラクター画像
│   ├── aniki1.png / aniki2.png # モジモンマスター用キャラクター画像
│   ├── bouken.webp          # ぼうけんモード画面
│   ├── quest.png            # クエスト画面
│   ├── screen_parent_gate.png # 保護者確認画面
│   ├── screen_settings.png  # 設定画面
│   ├── screen_success.png   # しゅぎょう成功画面
│   └── screen_unlock.png    # マスターパワー解放画面
├── move/                    # アプリ紹介・デモ用動画
│   ├── hiragana.MP4
│   ├── katakana.MOV
│   ├── kanji.MOV
│   ├── suuji.MOV
│   └── eigo.MOV
├── index.html
├── mojimon-master.html
├── tap-series.html
├── support.html
├── privacy.html
├── style.css
├── app-ads.txt
└── README.md
```

## 🖼️ 画像アセットの更新方法

各画面やキャラクター画像を更新したい場合は、`assets/` フォルダ内の対応する画像ファイルを上書き、またはHTML側のパスを変更してください。

- **キャラクター画像**: `assets/aniki.png`, `assets/aniki2.png`
- **モジモンマスター スクリーンショット**:
  - `assets/screen_success.png`（しゅぎょう成功）
  - `assets/bouken.webp`（ぼうけんモード）
  - `assets/quest.png`（クエスト）
  - `assets/screen_unlock.png`（マスターパワー解放）
  - `assets/screen_parent_gate.png`（保護者確認）

## 💻 ローカルでのプレビュー

ローカル環境で確認する場合は、静的サーバー（Python等のローカルサーバー）を起動してブラウザでアクセスしてください。

```bash
# Python 3 の場合
python3 -m http.server 8000
```
起動後、ブラウザで `http://localhost:8000/` にアクセスして確認できます。

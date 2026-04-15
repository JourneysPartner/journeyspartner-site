# 株式会社JourneysPartner コーポレートサイト

静的HTML/CSS/JavaScriptで構築した、株式会社JourneysPartnerの公式コーポレートサイトです。

## 構成

```
.
├── index.html          # 1ページ完結のトップページ
├── css/style.css       # サイト全体のスタイル
├── js/main.js          # モバイルメニュー用の最小限スクリプト
├── assets/
│   ├── company-profile.png  # 会社概要画像（原本そのまま）
│   └── contact-info.png     # 連絡先画像（原本そのまま）
├── netlify.toml        # Netlify設定
├── robots.txt
├── sitemap.xml
└── README.md
```

## ローカル確認方法

依存ライブラリはありません。任意の静的サーバで開くだけで動作します。

```bash
# Python が入っている場合
python -m http.server 8080
# → http://localhost:8080/ にアクセス
```

もしくは `index.html` をブラウザで直接開いても閲覧可能です。

## 更新方法

- テキストや構成変更 → `index.html` を編集
- 配色・余白・レスポンシブ → `css/style.css` を編集
- 画像差し替え → `assets/` 配下のファイルを同名で置き換え（会社概要・連絡先の2画像は原本を改変しない方針）

## 公開運用方針

- 本リポジトリは GitHub で管理します
- `main` ブランチへの push をトリガーに、Netlify が自動ビルド＆デプロイします
- 独自ドメイン未取得の間は Netlify のデフォルトサブドメイン（例: `https://<your-site>.netlify.app/`）で公開運用します
- 独自ドメインを取得した際は、Netlify 管理画面の Domain settings からカスタムドメインを追加することで移行可能です

## 掲載内容に関する注意

- 画像（`company-profile.png` / `contact-info.png`）は原本をそのまま掲載しています。OCR打ち直し・トリミング・文言改変は行っていません
- 正式な会社名表記は「株式会社JourneysPartner」（本文テキスト）です。画像内の「株式会社Journeys Partner」表記は原本のままとしています
- 最新の事業内容は、本文「主要サービス」「提携体制」セクションに記載しています
- 税務申告等の税務に関する専門対応は、提携先である毛利順活税理士事務所が担当します

## Google Ads API 利用方針

株式会社JourneysPartnerは、自社および提携サービスの集客を目的として、Google Ads API を社内の内部ツールとして利用しています。外部向けに販売するツールやサービスの開発には利用していません。

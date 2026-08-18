# 民泊物件ページ プレビュー / Vacation Rental Listing Preview

WordPress（Gutenberg ブロック）用のソース `wordpress-source.html` を、ブラウザで表示確認するためのプレビューリポジトリです。

## ファイル

| ファイル | 内容 |
|---|---|
| `index.html` | プレビュー用ページ（日本語版）。WordPressブロックソースを、レイアウトを再現するCSSで包んだ自己完結HTML。 |
| `wordpress-source.html` | WordPressに貼り付ける元のブロックソース（変更用ソース　羽田taji.html のコピー）。 |
| `en.html` | プレビュー用ページ（英語版）。日本語版の更新を反映した英訳版。 |
| `wordpress-source-en.html` | 英語版ページ用に WordPress に貼り付けるブロックソース（en-version.html のコピー）。 |

## 見方

`index.html`（日本語版）または `en.html`（英語版）をブラウザで開くだけです（ダブルクリック）。

公開URL:

- 日本語版: https://koishichito.github.io/vacation-rental-preview/
- 英語版: https://koishichito.github.io/vacation-rental-preview/en.html

- 画像は公開サーバー `vacation-rental.jnavi.co.jp` から読み込みます（要インターネット接続）。
- 実際のWordPressテーマのCSSとは細部のデザインが異なります。あくまで内容・構成の確認用です。

## 掲載物件

- **Kyoto** — ホテル楽々庵 / Sachi
- **Tokyo** — 羽田TAJI / 麻布十番
- **Osaka** — Ume / ビエラ江戸堀
- **Fukuoka**
- **Okinawa** — 今帰仁 / 越原 / 久貝 / 金武
- **Sapporo** — Suzuran
- **Kanazawa** — 凛 (Rin) / 奈々 (Nana) / 南町

## GitHub Pages で公開する場合

リポジトリを GitHub に push 後、Settings → Pages → Branch を `main` / `(root)` に設定すると、
`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開プレビューURLが得られます。

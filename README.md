# 紙マップでどこ？ 公式ページ

iOSアプリ「紙マップでどこ？」の公式 GitHub Pages 用ファイル一式。
Jekyll の Cayman テーマをベースに、ウォーム配色のカスタム CSS で装飾しています。

## ページ構成

| URL | ファイル | 用途 |
|---|---|---|
| `/kamidoko/` | `index.md` | アプリ紹介・使い方 |
| `/kamidoko/support.html` | `support.md` | サポート・FAQ（ASC Support URL） |
| `/kamidoko/privacy.html` | `privacy.md` | プライバシーポリシー（ASC Privacy URL） |

## 公開 URL

- アプリ紹介: <https://bobshiro.github.io/kamidoko/>
- サポート: <https://bobshiro.github.io/kamidoko/support.html>
- プライバシーポリシー: <https://bobshiro.github.io/kamidoko/privacy.html>

## ファイル

- `index.md` — アプリ紹介・使い方トップページ
- `support.md` — サポート・FAQ ページ
- `privacy.md` — プライバシーポリシー本文
- `_config.yml` — Jekyll 設定（theme: cayman、baseurl: /kamidoko）
- `assets/css/style.scss` — Cayman テーマの上書き CSS（フッター/ヘッダー非表示・ウォーム配色カード）

## デプロイ

main ブランチに push すると GitHub Pages が自動でリビルドし、1〜3 分で反映されます。

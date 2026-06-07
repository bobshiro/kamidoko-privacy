# 地図どこ＋ プライバシーポリシー

iOSアプリ「地図どこ＋」のプライバシーポリシーを GitHub Pages で公開するためのファイル一式です。
参照アプリ「アテンドコ」と同じ Jekyll Cayman テーマ構成になっています。

## 公開手順

1. GitHub で新しいリポジトリを作成します（例: `chizudoko-privacy`、Public）。
2. このフォルダの中身（`_config.yml` / `index.md` / `README.md`）をリポジトリにアップロードします。
3. リポジトリの **Settings → Pages** で、Source を「Deploy from a branch」、Branch を `main` / `(root)` に設定します。
4. 数分後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます。

## 公開前に差し替えるところ

- **連絡先メール**: `index.md` の2箇所（「1. 提供者」と「12. お問い合わせ」）にある `your-address@example.com`
- **URL**: `_config.yml` の `url` / `baseurl` を、作成したリポジトリに合わせて変更

## アプリ側の最後の作業

公開 URL が確定したら、Xcode プロジェクトの `Sources/LegalLinks.swift` にある
`privacyURL` を、この公開 URL へ差し替えてください
（自動更新サブスクのため、App Review では別途「利用規約（EULA）」の URL も必要です）。

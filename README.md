# booster-cs-calendar-generator

[![Cloudflare Pages](https://img.shields.io/badge/Cloudflare%20Pages-deployed-orange)](https://booster-cs-calendar-generator.pages.dev)

スケジュールカレンダー生成ツール。イベントスケジュールをカレンダー画像（PNG）として生成・ダウンロードできる、単一ファイルの静的 Web アプリです（`index.html` のみ、ビルド不要）。

## URL

https://booster-cs-calendar-generator.pages.dev

## Deployment

Cloudflare Pages の Git 連携でデプロイされます（GitHub Actions などの CI は不要）。

- Cloudflare アカウント: Repro Booster staging
- プロジェクト名: `booster-cs-calendar-generator`
- Production ブランチ: `main` — merge すると自動で本番デプロイされます
- その他のブランチへの push はプレビューデプロイが自動作成されます
- ビルドコマンド: なし / 出力ディレクトリ: `/`（リポジトリルートの `index.html` をそのまま配信）

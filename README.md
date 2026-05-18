# 変幻自在 / Hengenjizai

博多駅南・路地裏の十席の小さな居酒屋「変幻自在」公式サイト。

- 本番URL: https://hengenjizai-hakata.com
- ホスティング: Cloudflare Pages
- 連携: GitHub `ryuichi1124/hengenjizai` の `main` ブランチへのpushで自動デプロイ

## ローカル確認

```
open index.html
```

## デプロイ

`main` ブランチに push すると Cloudflare Pages が自動でビルド・公開します。

## 構成

- `index.html` — シングルページサイト
- `_headers` — Cloudflare Pages 用のセキュリティヘッダ・キャッシュ設定
- `robots.txt` — クローラー設定
- `sitemap.xml` — サイトマップ

---
title: Webに公式LINEリンクを載せる手順
tags:
  - proj/terakoya-nijigaoka
  - area/02-projects
date: 2026-06-02
---

# Webに公式LINEリンクを載せる手順

1. LINE Official Account Manager で **友だち追加URL** をコピー（例: `https://line.me/R/ti/p/@xxxxxxxx`）
2. `index.html` のリンク一覧に次を追加（`href` を実URLに差し替え）:

```html
<a href="LINE友だち追加URLをここに">💬 公式LINE<small>お休み・時間変更のお知らせ（任意）</small></a>
```

3. GitHub Pages へ反映（いつも通りのデプロイ手順）

QR画像を載せる場合は、管理画面からダウンロードした PNG を `_assets/line-qr.png` として置き、`<img>` で表示しても可。

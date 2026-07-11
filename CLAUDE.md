# daiya-links プロジェクト

## 概要

Instagram/TikTokのプロフィールに貼る「リンクインバイオ」ページ。Linktree(https://linktr.ee/da1yaai)の代替として、Claude Codeで作った自前のページ。GitHub Pagesで公開している。

## 公開URL

https://daiyamomorin.github.io/daiya-links/

## ファイル構成

- `index.html` — ページ本体（1ファイル完結、外部依存なし）

## デザイン

ダークネイビー×ネオングリーンのテック系デザイン。`02_PROJECTS/物販AI部/オープンチャット/画像/` のツール一覧インフォグラフィックと世界観を統一している。

## リンクの並び順

1. LINEオープンチャット「物販AI部」（最重要CTA、有料note販売の起点なので一番目立たせる）
2. TikTok
3. Instagram
4. Threads

## 更新方法

`index.html` を直接編集してpushすれば、GitHub Pagesが自動で反映する（数十秒〜数分）。

```bash
cd ~/daiya-links
git add index.html
git commit -m "update links"
git push
```

## 注意

- このリポジトリはpublic（GitHub Pagesの無料枠がpublicリポジトリ前提のため）。個人情報・売上データ・APIキーなど機密情報は絶対に置かない。
- DAIYA-LAB本体のリポジトリ（private）とは完全に別管理。

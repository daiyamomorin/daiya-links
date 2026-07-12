# daiya-links プロジェクト

## 概要

Instagram/TikTokのプロフィールに貼る「リンクインバイオ」ページ。Linktree(https://linktr.ee/da1yaai)の代替として、Claude Codeで作った自前のページ。GitHub Pagesで公開している。

## 公開URL

**https://da1ya-ai.pages.dev/**（Cloudflare Pages、本番。SNSプロフィールにはこれを貼る）

https://daiyamomorin.github.io/daiya-links/ （GitHub Pages、旧URL。本名のGitHubユーザー名が出るので使わない。放置でも害はないが優先しない）

どちらもリポジトリ`daiya-links`のmainブランチにpushすると自動で両方に反映される。

## ファイル構成

- `index.html` — ページ本体（1ファイル完結、外部依存なし）

## デザイン

Linktree(linktr.ee/da1yaai)と同じ配色・アイコンに合わせている。背景`#bfd1d7`、カード`#d6e3e8`、テキスト`#1c272b`のライトなセージカラー。アバターはTikTokのデフォルトアイコン画像(`avatar.jpg`)をLinktreeから取得して使用。

## リンクの並び順

1. LINEオープンチャット「物販AI部」（最重要CTA、有料note販売の起点なので一番目立たせる）
2. Instagram
3. TikTok
4. X
5. Threads

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

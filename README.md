# 発酵・地域フィールドワーク ナレッジライブラリ

料理教室、フィールドワーク、工場見学、発酵講座、商品開発相談の記録を整理した静的サイトです。

## 公開方法

GitHub Pagesで公開できます。

1. このフォルダの中身をGitHubリポジトリへアップロードする
2. GitHubの `Settings` から `Pages` を開く
3. `Deploy from a branch` を選ぶ
4. `main` ブランチ、`/root` を選んで保存する
5. 数分後に `https://ユーザー名.github.io/リポジトリ名/` で公開される

## 編集するファイル

- `index.html`: ページの骨組み
- `styles.css`: デザイン
- `app.js`: コンテンツ、検索、絞り込み、詳細表示
- `assets/fermentation-hero.png`: トップ画像

新しい記録を追加するときは、まず `app.js` の `contents` と `contentDetails` に追記します。

# CatoWorks Studio Website

CatoWorks Studio の公式ホームページを管理するリポジトリです。

## 公開方法

- 公開先: Netlify
- 公開対象: リポジトリ直下
- ビルドコマンド: なし
- 公開ディレクトリ: `.`

`main` は公開用の安定版です。更新は作業ブランチとPull Requestで確認してから `main` へ統合します。

## 主なファイル

- `index.html`: ホームページ本体
- `catodrive_development_note_v0_1.html`: CatoDrive開発ノート
- `assets/`: ロゴ、トップ画像、作品画像
- `netlify.toml`: Netlify の公開設定

## 更新方針

1. 作業ブランチで変更する
2. Draft PRで画面と文章を確認する
3. 問題がなければ `main` へマージする
4. Netlifyが `main` を自動公開する

本リポジトリへの初回移植では、2026年7月7日にNetlify Dropで公開されたページの見た目と内容を維持しています。HTML内に埋め込まれていた画像は、管理しやすいよう `assets/` へ分離し、WebPへ軽量化しています。

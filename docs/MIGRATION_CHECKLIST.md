# Netlify Git連携 移行チェックリスト

このチェックリストは、現在Netlify Dropで公開中のCatoWorks Studioサイトを、GitHub管理へ安全に切り替えるためのものです。

## PRをマージする前

- [ ] ホーム画面の横長ロゴが表示される
- [ ] ヒーロー画像が表示される
- [ ] ライチサバイバーズ画像が表示される
- [ ] ○×ゲーム画像が表示される
- [ ] CatoDrive開発ノートを開ける
- [ ] PC表示を確認する
- [ ] スマホ表示を確認する

## PRをマージした後

- [ ] Netlifyで既存サイト `catoworks-studio` を開く
- [ ] GitHubリポジトリ `nekosuke66/catoworks-studio-site` を接続する
- [ ] Production branchを `main` にする
- [ ] Build commandは空欄にする
- [ ] Publish directoryは `.` にする
- [ ] 初回デプロイのPreviewを確認する
- [ ] 問題がなければ既存URLの公開先をGit連携へ切り替える

## 安全方針

- Git連携が正常に動くまで、現在のNetlify Drop公開は残す
- `main`へ直接変更を入れず、別ブランチとPull Requestを使う
- 公開後に問題が出た場合は、Netlifyの直前デプロイへ戻す

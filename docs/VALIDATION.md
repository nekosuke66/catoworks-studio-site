# 移植時の確認結果

## 構成確認

- `index.html` がリポジトリ直下にある
- `netlify.toml` のPublish directoryは `.`
- HTMLが参照するWebP画像5枚が `assets/` にある
- CatoDrive開発ノートがリポジトリ直下にある
- 現在のNetlify Drop公開先はまだ変更していない

## このPRでは行わないこと

- 既存NetlifyサイトのGit連携切り替え
- 公開URLの変更
- OBS簡単接続エディタの作品カード追加
- SNS投稿

これらは移植PRの確認・マージ後に、別作業として進める。

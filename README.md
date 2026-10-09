# 100_balls_calculator

100玉そろばんの計算機と、それを使った算数ゲーム（単体 HTML、データ無し）。GitHub: `100_calculator`。

- `index.html` … 100玉そろばん計算機。画面下のリンクからゲームへ
- `game.html` `game2.html` `game3.html` `game4.html` … ゲーム1〜4
- `assets/audio/` … 効果音・BGM
- `docs/` … 仕様と実装計画

## 利用

利用する場所はこの repo の clone。そこでは直さず、開発側で直してコミットし、clone 側の `update.command`（`git pull --ff-only`）で取り込む。

- 正本: 無し（データを持たない app）。clone には起動口・README・コードだけがある
- 起動: `start.command` をダブルクリック（clone の `index.html` をブラウザで開く。ゲームは画面下のリンクから）
- 取り込み: `update.command` をダブルクリック

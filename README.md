# 100_balls_calculator

100玉そろばんの計算機と、それを使った算数ゲーム（単体 HTML、データ無し）。GitHub: `100_calculator`。

- `index.html` … 100玉そろばん計算機。画面下のリンクからゲームへ
- `game.html` `game2.html` `game3.html` `game4.html` … ゲーム1〜4
- `assets/audio/` … 効果音・BGM
- `assets/feedback.js` … 右上の ! （改善のコメント）。共通の部品（issue_hub/feedback/feedback.js）をそのまま写したもの
- `docs/` … 仕様と実装計画

## 改善のコメント（右上の !）

どのページでも、右上の ! を押すと改善のコメントを書く窓が開く。

- 「GitHub を開く」で、この repo の新しい Issue の画面が開く。題名と本文には、画面 ID（`game3.village` など）・コメント・今の状態（どのゲーム・どのタブかなど）が書き込み済み。「Create」で送る
- repo は公開なので、送った中身は誰でも読める。画面の写真は初めは付けない（付けるを選んだときだけ）
- 写真を付けると、写真は端末に保存される。GitHub の画面に自分で添付して送る

## 利用

利用する場所はこの repo の clone。そこでは直さず、開発側で直してコミットし、clone 側の `update.command`（`git pull --ff-only`）で取り込む。

- 正本: 無し（データを持たない app）。clone には起動口・README・コードだけがある
- 起動: `start.command` をダブルクリック（clone の `index.html` をブラウザで開く。ゲームは画面下のリンクから）
- 取り込み: `update.command` をダブルクリック

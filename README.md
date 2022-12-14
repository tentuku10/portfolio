## サービス概要
簡単な操作で駅や現在地周辺にある「居酒屋」を検索してグーグルマップ上に表示するサービスです

## メインのターゲットユーザー
- 飲むなら居酒屋がいい人
- 急な飲み会でもお店を外したくない人
- 首都圏など飲める場所が多すぎる地域に住んでる人
- 業務中に飲みが決まってその日の15時くらいから居酒屋を探す人
- 居酒屋を探すことが苦手、面倒だけど探す必要がある人

## ユーザーが抱える課題
- 首都圏は居酒屋が多くてそもそも探すのが大変
- お店選びに失敗してしまい盛り上がりに欠ける飲み会になってしまうことがある

## 解決方法
- 駅や現在地周辺の居酒屋を少ない操作でグーグルマップ上に表示
- あらかじめ抽出条件を設定し、あえて選択肢を絞ることで選択しやすくする（コンセプトとしては、いい居酒屋を探すというよりは評判のあまり良くない居酒屋を選択肢に挙げないという感じ。どのような条件がいいかはユーザーのフィードバック込みで考えていきたい）

## 実装予定の機能
【MVP】
- 居酒屋検索機能
  - 現在地から検索する機能
  - 駅名から検索する機能
- グーグルマップ上に居酒屋を表示（まずは東京）
- 居酒屋の一覧・詳細
- ログイン機能
- お気に入り機能
- お気に入りリスト
- LINEで共有する機能
- Google Maps APIを使用（予定）

【本リリース】
- 居酒屋検索機能追加
  - フリーワードで検索する機能
  - カテゴリから検索する機能
- ユーザーからのフィードバックをもとに抽出条件を追加
  - 営業中の居酒屋のみ表示できる機能
  - 価格帯による分類
  - 平均的な混み具合など
- 対象エリア拡大
  - 居酒屋取得エリアを追加
  - 検索できる駅名を追加 
- 管理ユーザーの一覧、詳細、作成、編集、削除

【本リリース後（可能なら）】
- 口コミ分析結果を抽出条件として加える

## なぜこのサービスを作りたいのか？
- 自分の人生を振り返ってみると「居酒屋で飲む」ことを通していろいろな人と良い関係性を築けてきた
- 楽しい飲み会であったかどうかの条件として居酒屋の雰囲気なども自分にとって重要なものである
- 東京は居酒屋の数が多いので、特に馴染みのない駅で飲むとき居酒屋を探すのに苦労している
- 簡単に「大きくは外さない居酒屋」を検索できるサービスを開発することで、同じような考えを持つ人に価値を提供したい
- なにより自分が使いたい

## スケジュール
- 企画〜技術調査：11/17〆切
- README〜ER図作成：11/27 〆切
- メイン機能実装：11/28 - 1/27
- β版をRUNTEQ内リリース（MVP）：1/28〆切
- 本番リリース：2月中旬

## 画面遷移図
[Figma]https://www.figma.com/file/QuXLXaw2MpuG3dvyXG0tPQ/portfolio?node-id=0%3A1&t=DIWzj557JJSPxhDU-0

## ER図
https://drive.google.com/file/d/19kX_y1aUWy0p8mk6DwMuigQJr8SPl9fe/view?usp=sharing
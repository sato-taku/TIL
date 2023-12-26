# マルチ検索・オートコンプリート
一文字入力するたびに候補が表示される
### 使用技術
- Stimulus Autocomplete (Rails7)
 - https://github.com/afcapel/stimulus-autocomplete
- JQuery
 - https://github.com/xpeppers/rails-autocomplete

# 通知
お知らせをリアルタイムで通知
WebSocket通信 ActionCable (Rails標準)

# LINE通知
### 使用技術
- LINE Messaging API
- LINE Messaging API SDK for Ruby
 - https://github.com/line/line-bot-sdk-ruby

# レコメンド
協調フィルタリング…ユーザの行動や嗜好データをもとに類似度を算出
コンテンツフィルタリング…コンテンツの数値化された特徴や評価をもとに類似度を算出
### 使用技術
- Amazon Personalize
 - https://docs.aws.amazon.com/ja_jp/personalize/latest/dg/what-is-personalize.html
 - AWSが提供
- GCP Recommendations AI
 - https://cloud.google.com/recommendations?hl=ja
 - Google　Cloud Platformが提供
- アルゴリズム
 - 一般的にアルゴリズムが公開されている

# チャット
WebSocketを用いることでリアルタイムでやり取りが可能
### 使用技術
- WebSocket
 - https://ja.wikipedia.org/wiki/WebSocket
- ActionCable（Rails標準）
 - https://railsguides.jp/action_cable_overview.html

# 画像加工・合成
画像サイズを揃える→表示を統一化
文字を合成→OGPをよりわかりやすくする
ユーザビリティの向上
### 使用技術
- ImageMagick
 - https://imagemagick.org/index.php
 - 画像を操作・加工できる
- RMagick
 - https://github.com/rmagick/rmagick
 - RubyからImageMagickを利用できるようにする。CarrierWaveとセットで使われること多い
- MiniMagick
 - https://github.com/minimagick/minimagick
 - RMagickの省メモリ設計、機能は制限される
- Cloudinary
 - https://cloudinary.com/
 - https://cloudinary.com/products/programmable_media
 
 # ステップ入力・確認画面
 フォームを複数のステップに分割
 確認画面を挟む

 # 位置情報
 ### 使用技術
- Google Maps Platform
 - https://mapsplatform.google.com/intl/ja/
- Geocorder
 - https://github.com/alexreisner/geocoder
 - 住所や地名から位置情報を取得することができる、逆もできる。

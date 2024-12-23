# 2024.11.11の学習記録

## 📚 学習内容
- メモアプリ作成(完了) 
  - 削除機能
  - 編集機能
  - エラーの確認、バグ修正
  - コードの整理 ←リファクタリング
- じゃんけん＋あっち向いてほいアプリ作成 👉 進行中
  - 機能要件整理、処理フロー検討
  - じゃんけんの流れ整理

## 💭 思ったこと
- CLIアプリ(ターミナルで動くアプリ)の特徴・制約
  - スマホやPCのメモアプリのように、現在の内容を表示しながら編集ということができないと知って衝撃
  - 1行ずつの実行ってそういうことか…
    - なので「すべて書き直し」か「追記」を選べるようにした！
- `CSV.parse`と`CSV.read`の違い
- 例外処理について
  - 問題が起こりそうなすべての箇所に入れなければならないのか…？と思った
  - が、調べていたら下記のような外部とやり取りする場合に特に必要そうだと分かった
    - ファイル操作
    - ネットワーク通信
    - データベース操作
   
### ✨ 開発の感想
- 全体がうまく動くと嬉しい！
- でも気になるところが次々と見つかる
  - 表示の細かい部分
  - コマンド入力のタイミング
- キリがないので諦めも大事かもしれない…今の力では…

## 🚀 これから
- じゃんけん＋あっち向いてほいアプリの続き
  - じゃんけん勝敗ロジック
  - あっち向いてほいの流れ、勝敗ロジック
  - じゃんけんからあっち向いてほいに自然に流す方法

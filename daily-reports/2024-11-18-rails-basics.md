# 2024.11.13 の学習記録

## 📚 学習内容

- Rails 基礎概念
- Rails 環境構築

## 💭 思ったこと

- 環境構築でとても時間がかかった！
  - 指定されたバージョンではなく、誤って最新バージョンを一度インストールしたところ何度再インストールしても最新が残ってしまう状態に陥った
  - Rubyインストールからのやり直しを重ね無事インストールできた
- が、new コマンドでテストしたところまた異なるバージョンになってしまった…
  - 試して正解だったこと
    - Node.js、Yarn をインストール
    - Gemfile に`gem 'psych', '~> 3.1'`を追記し、bundle、webpacker を再インストール

## 🚀 これから

- Rails 学習に入る

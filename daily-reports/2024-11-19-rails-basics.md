# 2024.11.19の学習記録

## 📚 学習内容
- CRUD処理
  - Read
  - Update
  - Delete
- リレーション
- バリデーション

## 💭 思ったこと
- 削除リンクの実装方法の違い
  - link_to   
  `<%= link_to "削除", user, method: :delete, data: { confirm: "本当に削除しますか?" } %>`
  - button_to  
    `<%= button_to "削除", user_path(user), 
    method: :delete, 
    data: { confirm: "本当に削除しますか?" }
    %>`
  - button_toはJavaScript無効でも動くからより確実に使えそう

## 🚀 これから
- RSpec
- デバッグ

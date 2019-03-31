# flask_get_favorites
FirebaseでTwitterアカウント認証したユーザーの「いいね」ツイートを100件取得するためのAPI  
結果を[Vue.js](https://github.com/yookm19/flask_get_favorites)に渡しています。

## アプリ画面
<img src="images/result1.png" width=50%>

## 実行方法
```
python get_favorites.py
```

## 詳細
- user_idが現状固定されているので、引数として変更できるようにしてください
- CONSUMER_kEYなどを自分のものに変えてください
- countの部分も自由に変えてください
- top.htmlに結果が反映されるようにしています。

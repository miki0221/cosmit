# アプリケーション名
Cosmit

# アプリケーション概要
所有するコスメを登録し、所有するコスメの共有・使用期限を管理することができるアプリ。

Cosmetic × Merit × Limit = Cosmit

# URL
https://cosmit.onrender.com

# テスト用アカウント
- Basic認証ID：admin
- Basic認証Pass：2222
- Email：test1@test.com
- Password：test111

# 利用方法
1. トップページ（一覧ページ）のヘッダーからユーザー新規登録を行う
2. コスメ登録ボタンからコスメの内容（画像・カテゴリー・ブランド名・コスメ名・フリーワード（特徴・使用感など）使用開始日））を入力し登録する
3. トップページから詳細ページに移動し、自分が登録したコスメであれば編集・削除ができる
4. トップページから詳細ページに移動し、他者が登録したコスメであればお気に入り登録ができる

# アプリケーションを作成した背景
- コスメが増えるにつれて所有するコスメの把握ができなくなってきた。
- コロナ禍になってからコスメの使用頻度が下がっていることもあり、
使用期限が切れてしまうことが増えてきた。
- 他のユーザーがどういったコスメを使用しているか気になる。

以上のことからコスメ共有・管理アプリを開発することにした。

# 洗い出した要件
修正中

# 実装した機能についての画像やGIFおよびその説明
## ユーザー登録
[![Image from Gyazo](https://i.gyazo.com/636ea7965cb13d6346ddec7d6a1d692b.gif)](https://gyazo.com/636ea7965cb13d6346ddec7d6a1d692b)
## ユーザーログイン
[![Image from Gyazo](https://i.gyazo.com/2d2ca739ecff96b886ae0e47c6ebc85a.gif)](https://gyazo.com/2d2ca739ecff96b886ae0e47c6ebc85a)

## コスメ登録(投稿)
[![Image from Gyazo](https://i.gyazo.com/816782b3e01089f5ad1351a84fbfdc28.gif)](https://gyazo.com/816782b3e01089f5ad1351a84fbfdc28)

## 一覧表示
[![Image from Gyazo](https://i.gyazo.com/c1fb1b5dbcc007b080c171cc90286587.gif)](https://gyazo.com/c1fb1b5dbcc007b080c171cc90286587)

## 詳細表示
[![Image from Gyazo](https://i.gyazo.com/1d6f07e91d6c636a58f9655c7b68d9b5.gif)](https://gyazo.com/1d6f07e91d6c636a58f9655c7b68d9b5)

# 実装予定の機能
現在はマイページ機能を実装中。
今後は編集・削除・お気に入り機能などを実装予定

# データベース設計
[![Image from Gyazo](https://i.gyazo.com/f632ab3808a2e7251b7d66180b029878.png)](https://gyazo.com/f632ab3808a2e7251b7d66180b029878)

# 画像遷移図
[![Image from Gyazo](https://i.gyazo.com/b6d9bda5e23285ede3307fde32259bb9.png)](https://gyazo.com/b6d9bda5e23285ede3307fde32259bb9)

# 工夫したポイント
- カテゴリーごとに一覧表示を分けたこと。
- 詳細カテゴリーによって使用期限を分け、コスメ使用開始日から使用期限までの残数を表示すること。

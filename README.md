[![Image from Gyazo](https://i.gyazo.com/1f93b855527ad983efb86506e9660925.png)](https://gyazo.com/1f93b855527ad983efb86506e9660925)

## サービス概要
RUNTEQコミュニティに所属する人々のプロフィール情報を、集約し、見やすく表示するサービスです。
生成するイメージ画像をtwitterに投稿あるいは、アプリケーション内で表示することで、
ユーザーのプロフィールを見た人にユーザーについて知ってもらう機会を提供します。
20年前に女子の間で流行したプロフィール帳をイメージしたアプリケーションになります。

サービスURL: https://readmeee.vercel.app

Githubリポジトリ

- フロントエンド 
https://github.com/mitsu30/Read_me_frontend
- バックエンド
https://github.com/mitsu30/Read_me_backend

## なぜこのサービスを作りたいのか？
せっかくコミュニティがあるので、メンバー間のコミュニケーションのきっかけになればいいなと考えています。
モチベーションが下がった時に励ましあったり、プログラミング学習について教えあったりなど、
RUNTEQにコミュニティがあることはとても大きいと感じています。
ただ、オンラインのコミュニティというところもあり、コミュニティの参加に心理的なハードルがあったり、
相手の情報を知らず、コミュニケーションのきっかけを掴めないという方もいらっしゃると思います。
メンバーの詳細について少しでも知ることができれば、コミュニケーションのきっかけとなり得ると思いました。

## メインのターゲットユーザー
RUNTEQコミュニティに属する方々です。

## ユーザーが抱える課題
RUNTEQの受講生がコミュニティ参加の際に以下のような心理的なハードルがあること。
・会話のきっかけを見つけるのが難しい。
・他のメンバーについてそもそも知らない。

## 解決方法
受講生のプロフィール情報を期ごとにまとめて、ユーザーの情報を見やすくする。ファンシーなデザインによってTwitterにシェアしやすくし、ユーザーのプロフィール入力を促進する。
また、アプリケーションを閲覧した人に別のユーザーの存在を認知させる。

## 機能紹介
| トップページ | おためし作成 |
|----------|-------|
|[![Image from Gyazo](https://i.gyazo.com/40d497497fc27a848286881705374a35.jpg)](https://gyazo.com/40d497497fc27a848286881705374a35)|[![Image from Gyazo](https://i.gyazo.com/705850a495dfd3ac4ad4ae32bf0a5db4.jpg)](https://gyazo.com/705850a495dfd3ac4ad4ae32bf0a5db4)|
||自分のプロフィールを入力します|

| プレビュー | 作成結果出力 |
|----------|-------|
|[![Image from Gyazo](https://i.gyazo.com/4ef70e01b842842492fd1b5c53619ad5.gif)](https://gyazo.com/4ef70e01b842842492fd1b5c53619ad5)|[![Image from Gyazo](https://i.gyazo.com/5645a8cb7d0199814a3760a5a5df9ced.gif)](https://gyazo.com/5645a8cb7d0199814a3760a5a5df9ced)|
|プレビューで入力した内容をすぐに確認できます|つくるでプロフィール帳を作成します|

| Twitterシェア | ログイン |
|----------|-------|
|[![Image from Gyazo](https://i.gyazo.com/7df942c2b26b2ed5121b2a5a27c900a6.png)](https://gyazo.com/7df942c2b26b2ed5121b2a5a27c900a6)|[![Image from Gyazo](https://i.gyazo.com/2ce8d2c182627683b66145eab8b74613.gif)](https://gyazo.com/2ce8d2c182627683b66145eab8b74613)|
|Twitterでシェア！|クリックするだけで自動でログイン|

| スクールユーザー一覧ページ | スクールユーザー詳細ページ |
|----------|-------|
|[![Image from Gyazo](https://i.gyazo.com/6ffb2f486e3e915958411d9553df2448.png)](https://gyazo.com/6ffb2f486e3e915958411d9553df2448)|[![Image from Gyazo](https://i.gyazo.com/c899b12bb6f2503fbd5a309d07194d6c.jpg)](https://gyazo.com/c899b12bb6f2503fbd5a309d07194d6c)|
|||

| プロフィール帳公開範囲の設定 | ログインユーザー用プロフィール帳 |
|----------|-------|
|[![Image from Gyazo](https://i.gyazo.com/608f2c2c963c28b0f8e290aa31f22745.jpg)](https://gyazo.com/608f2c2c963c28b0f8e290aa31f22745)|[![Image from Gyazo](https://i.gyazo.com/86e6298a4a411a55034c38ccaced3e78.jpg)](https://gyazo.com/86e6298a4a411a55034c38ccaced3e78)|
||スクールユーザーのみ「すくーる」を使用可能|

| 動的OGPの設定 | |
|----------|-------|
|[![Image from Gyazo](https://i.gyazo.com/1efddf9af4ce274bfe5f72ace49a0850.png)](https://gyazo.com/1efddf9af4ce274bfe5f72ace49a0850)||
| Twitterシェアする際にデフォルト画像を設定できる||


## 各ユーザーの権限
⬜️ 一般ユーザー
- プロフィール帳の作成（使えるデザインは1種類のみ）
- Twitterシェア
- GitHubログイン


⬜️ 登録ユーザー
- GitHubログインで下記ユーザー権限に自動振り分け
・スクール関係者
・一般ユーザー

▫️ 登録ユーザー（スクール関係者）
- プロフィール帳の作成、保存、削除（使えるデザインは3種類）
- 各プロフィール帳の公開範囲の設定
- Twitterシェア
- Twitterシェア時のOGP画像の設定
- ユーザー情報の登録、編集
- スクール関係者のユーザー一覧の閲覧
- スクール関係者のユーザーの「なまえ」での検索、「登録日時」と「なまえ」でのソート、「期」でのグループ化
- スクール関係者のユーザー詳細情報、プロフィール帳の閲覧
- ログアウト

◽️ 登録ユーザー（一般ユーザー・スクール関係者と異なる点）
- プロフィール帳の作成、保存、削除（使えるデザインは2種類）
- スクール関係者のユーザー一覧の閲覧(ただし「スクール」に所属するユーザーのアバター画像はデフォルトで設定したもの(人型アイコン)になる。)

## 今後の展望
- 管理者画面
- googleログイン機能（一般ユーザー向け）
- 新たにコミュニティの作成
- 他ユーザーが作成したコミュニティへの参加
- プロフィール帳に記載した内容からフリーワードでユーザーを検索


## 主な使用技術

### フロントエンド
- Next.js
- React.js
- MUI
- Axios
- Next-SEO
- Nookies
- Notistack
- React-Paginate

### バックエンド
- Ruby on Rails(APIモード)
- mini_magick 
- rack-cors
- jwt
- aws-sdk-s3
- octokit
- kaminari

### インフラ
- vercel
- Fly.io
- S3

### その他
- Firebase Authentication
- GitHub API

## ER図
[![Image from Gyazo](https://i.gyazo.com/8ef80deec03638284f0202e91e619d15.png)](https://gyazo.com/8ef80deec03638284f0202e91e619d15)




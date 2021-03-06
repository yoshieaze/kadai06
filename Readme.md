# 課題06 PHP
## Docker + Laravelを利用して、CRUD機能を実装する

## 1. 操作方法、実装内容
### 課題説明
- Laravelを予習で使ってみたいと思い、Docker上で実装しました
- Laravel Genratorを利用して、CRUD機能を実装しています
- ユーザーごとにタイトルとメモが記録できる簡易的なメモアプリになっています

### 操作方法
#### ログインまで
- Docker上で動作を確認しました。Makefileを用意してあり、ターミナルよりmake upでDockerが立ち上がります。
- localhost:8000でSimple Notesというタイトルとトップページが表示されます
- 背景画像はUnsplashのRandom機能を利用して読み込みごとに変わるようになっています
- 画面右上にLogin, Register(ログイン後はHome)が表示されます
- 新規ユーザーはRegister機能よりユーザー登録可能です。User Termなどは用意していません
- Loginできるユーザーはtest@test.com,test2@test.comで動作確認可能です。

#### Home画面の説明
- 画面右側にサイドメニューが表示されます。Postsをクリックすると、メモ帳が表示されます
- サイドメニューの右横にハンバーガーメニューが表示されます。クリックするとサイドバーが最小化します
- 画面右横にログインユーザーが表示されます。クリックしてProfileを押すと、登録したプロフィールの確認ができます

#### Postsの説明
- Postsを開くと、過去に登録したメモが一覧で表示されます。名前、タイトル、メモ内容、アクションが表示されています
- 画面右上のAdd Newボタンをクリックすると、新規メモを登録できる画面に遷移します
- タイトルと内容のどちらも入力する必要があります。入力後、Saveボタンをクリックすると、保存されて一覧画面に遷移します
- Actionの目のアイコンマークは、登録内容の確認ができます
- Actionの鉛筆マークは、登録内容の編集ができます
- Actionのゴミ箱マークは、データを削除することができます


## 2. 実装の工夫
- 基本的にYouTube動画を見つけた写経になっています。https://youtu.be/nzVSzEv0Zy0
- YouTubeだとユーザーごとにメモのデータが絞られてなかったので、絞られるようにしました
- Top PageのデザインはUnsplashのランダム機能を利用しています

## 3. 感想、疑問点
- Docker, Laravel, Git, Laravel Generatorと新しいことばかりで理解が追いつきませんでしたが、
  コマンドラインからGitにアップロードできたり、フレームワークの便利さを実感したり、
  技術的にこんなことできるのか！と発見が多い写経になりました
- 自分でプロファイルページを編集できるようにしたかったのですが、そこまでたどり着けず、、、
  次回はGenratorを使わずに実装する方向でトライしたいと思います。






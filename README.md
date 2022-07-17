# 原神デイリーログインボーナス

Github Actions でデイリーログインボーナスを自動で受け取る

[English](README.en.md)

# 導入方法

1. このリポジトリをフォークする
2. Settings -> Secrets に移動する
3. `New repository secret"`のボタンを押す
4. あなたの認証情報を下記の手順で入手し、 `LTUID`、 `LTOKEN` の secrets 変数を作る
5. Actions のページに行き、`Enable Actions Workflow`ボタンを押す
6. 左の workflow list から`HoYoLAB Attendance`を選び`Enable Workflow`ボタンを押す
7. 準備完了！毎日 01:00 JST に自動でログインボーナスを受け取れる

# 認証情報の入手方法

Chrome のデベロッパーツールを想定:

1. [HoYoLAB](http://hoyolab.com)にアクセスする
2. 自分のアカウントでログインする
3. `F12`を押してデベロッパーツールを開く
4. アプリケーション -> Cookies -> `https://www.hoyolab.com`に移動する
5. `ltuid`と`ltoken`の値をコピーする

# ライセンス

[MIT License](LICENSE)

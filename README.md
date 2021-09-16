# Dockerでwebサーバーを起動する
以下の手順でwebサーバーが起動していることを確認してください

1. Visual Studio Codeを起動する。
2. このリポジトリをクローンする
3. Visual Studio Codeのターミナルメニューから「新しいターミナル」を実行します。
4. Windowsの方は"win_docker_run.bat"を実行（"win_docker_run.bat"と入力してENTER）し、Macの方は"mac_docker_run.sh"を実行（"zsh mac_docker_run.sh"と入力してENTER）します。
4. "root@8a4557ad22e9:/opt#"のような表示がでていることを確認する。
5. "npx http-server"を実行する。（"npx http-server"と入力してENTER）
6. "Ok to proceed? (y)"という表示がでたら、"y"を押す。
7. webサーバーの準備が実行され、"Hit CTRL-C to stop the server"が表示されたらwebサーバーの起動完了。

この時点で以下の表示になります（Windowsの場合）
![](win.png)

8. ブラウザのアドレスバーに"http://localhost:8080/"を入力。
9. ブラウザの画面に"Hello, world!"が表示されたらOK。
10. 同じディレクトリの"index.html"の内容を変更して、ブラウザをリロード（再読み込み）した時に表示内容が変わっていることを確認してください。
11. 動作確認が終わったら、Ctrl+cでサーバーを終了し、exitでDocker環境を終了してください。
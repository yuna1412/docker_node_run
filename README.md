# Dockerでwebサーバーを起動する
以下の手順でwebサーバーが起動していることを確認してください

## Windowsの場合
1. このリポジトリをクローンする
2. PowerShellを起動し、リポジトリのディレクトリに移動する。
3. "win_docker_run.bat"を実行する。（"win_docker_run.bat"と入力してENTER）
4. "root@8a4557ad22e9:/opt#"のような表示がでていることを確認する。
5. "npx http-server"を実行する。（"npx http-server"と入力してENTER）
6. "Ok to proceed? (y)"という表示がでたら、"y"を押す。
7. webサーバーの準備が実行され、"Hit CTRL-C to stop the server"が表示されたらwebサーバーの移動が完了
8. ブラウザのアドレスバーに"http://localhost:8080/"を入力。
9. ブラウザの画面に"Hello, world!"が表示されたらOK。
10. 同じディレクトリの"index.html"の内容を変更して、ブラウザをリロード（再読み込み）した時に表示内容が変わっていることを確認してください。
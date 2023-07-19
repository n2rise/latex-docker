VSCodeとDockerを使ってLaTeXを書く環境(個人メモ)
1. Dockerをインストール
2. 以下のコマンドを入力
```shell
$ git clone git@github.com:n2rise/VSCode-Docker-LaTeX-Config.git
$ code --install-extension ms-vscode-remote.remote-containers
$ code ./VSCode-Docker-LaTeX-Config
```
3. VSCodeでコマンドパレットorリモートウィンドウを開き，`Reopen in Container(コンテナーで再度開く)`を選択

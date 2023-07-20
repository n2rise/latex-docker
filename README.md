VSCodeとDockerを使ってLaTeXを書く環境(個人メモ)
1. VSCodeとDockerをインストール
2. 以下のコマンドを入力
```shell
$ code --install-extension ms-vscode-remote.remote-containers
$ git clone git@github.com:n2rise/latex-docker.git
$ code ./latex-docker
```
3. VSCodeでコマンドパレットorリモートウィンドウを開き，`Reopen in Container(コンテナーで再度開く)`を選択

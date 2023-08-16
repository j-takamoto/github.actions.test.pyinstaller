# github.actions.test.pyinstaller

### PythonアプリをPyInstallerでexe化して、Releaseするサンプルです
### Workflowは先頭に"v"のついたタグをPushした際に実行します

## タグPush手順

 通常通りに変更ソースをcommit&push後に以下の手順を実行
 
 - コマンドで行う場合

 1. タグの作成 `git tag v1.1` (タグ名は先頭にvがついていればOK)
 1. タグをPush `git push origin --tags`

- VSCodeで行う場合
 1. コマンドパレットから `Git: Create Tag`(Git: タグを作成)を実行
 1. タグを入力しEnter
 1. メッセージは任意で入力しEnter
 1. コマンドパレットから `Git: Push Tags`(Git: タグをプッシュ)を実行
 1. Pushするリモートを選択しEnter

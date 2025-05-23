# git add
リポジトリに追加したい対象を指定する
```sh
git add <filepatterrn>
```
通常全てのファイルをリポジトリに追加したい場合は
```sh
git add .
```

# git init
Git管理を開始するコマンド
```sh
git init
```

# git reset
ステージングエリアをGitリポジトリの状態に戻す
```sh
git reset HEAD <file>
```
ここでいう`HEAD`とは現在動かしているローカルリポジトリ(多分)

# git checkout
ステージングエリアの状態をワークツリーに持ってくる。
```sh
git checkout -- <file>
```

# git branch
現在のコミットからブランチを切れる。
```sh
git branch <branch名>
```

# git checkout <branch名>
作業中のブランチを切り替える。
```sh
git checkout <branch名>
```

ブランチを切りながら切り替えるには
```sh
git checkout -b <old> <new>
```
# git fetch
リモートの情報をローカルのリポジトリに持ってくる。
```sh
git fetch
```

# git pull
リモートの情報をワークスペースに持ってくる。
```sh
git pull
```

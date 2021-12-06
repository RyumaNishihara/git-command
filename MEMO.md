# git 学習

## git コマンド

ローカルリポジトリを作る。
$ git init

ステージングエリアにファイルを登録
$ git add

git ディレクトリにコミット
$ git commit
（VScode が開かれてメッセージを記載する）

$ git commit -m "ココにメッセージ記載"

ファイルの状態を確認
$ git status

ワークツリーとステージングエリアの差分を確認
$ git diff

ステージングエリアと git ディレクトリの差分を確認
$ git diff --cached

ワークツリーの変更を取り消す
$ git checkout -- ファイル・ディレクトリ名

ステージングエリアへの登録を取り消す
$ git reset HEAD ファイル・ディレクトリパス

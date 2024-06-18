# ToDo管理アプリ

## 作成した背景

大学のプログラミングの授業で、Javaを使ってTODO管理システムを作るという課題がありました。
この課題は、最大三人でチームを組んで取り組むことができる課題で、私は二人でチームを組んで取り組みました。

## 実行方法
```sh
git clone git@github.com:hikaru2003/ToDoList.git
cd ToDoList
make
```
GUIフレームワークはswing

## こだわった点

あまりきっちりと担当を分けてはいないのですが、主にフロントエンドの作成を担当
見やすさ、使いやすさにこだわった
* チェックボックスは、直接クリックしたときだけ反応するのではなく、右側のtitleやpriorityなどの要素をクリックしても反応するようにした。これは、チェックボックスをクリックするよりもtitleをクリックする方が直感的に操作しやすいと思ったからである
* ページの遷移をするボタンは、リンクであることがわかりやすいように赤色にしてアンダーラインをつけた
* リストの数が多くなり、ウィンドウに納まらなくなる可能性があるので、スクロール機能を追加した
* Webサイトでよく見るログイン画面やアカウント作成画面、ボタンの形を意識した

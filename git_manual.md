# GitHub Desktopを用いた開発の手順
作業を行う上でのGitHub Desktopの使い方を自分たちなりにまとめる。

## Clone（初回のみ）  
Cloneを取得したいリポジトリの場所にブラウザから飛ぶ。  
例：https://github.com/[Organizations]/[Repository]  
「Clone or download」→「Open in desktop」でGithub desktopに登録される。  
（この際、GitHub desktopがインストールされていなければ、GitHub desktopのダウンロードページへ飛ばされたりする）  

## Sync
Syncボタンを押すと自動でSync(=同期)が行われる。  
後述の手順を踏む前に必ずSyncすること。  
エラーの原因になる。  

## ブランチ切る
ブランチを切る＝新しいブランチを作成する  
GitHub Desktopの右上にある"Create new branch"を押す。  
そして、Nameを入力して、UI下部のCreate new branchをクリックすれば新しいブランチが作成される。  
Nameには、"変更者の署名/自分がこれからやるつもりの作業"を入力すれば他者にもわかりやすい。  
なお、Nameには英数字しか入力ができないので注意。  

## 作業
好きにやる。

## コミット
コミットしたいファイルを選ぶ。  
Sumallyに説明をいれる。  
必要であればDescriptionをいれる。  

## Sync
コミットが終わったら念のためもう一度Syncしておく。  
コミットしていない（自らが記述した）変更点があった時はSyncができないので  
更新状態を最新にしつつ、コミットし忘れを防ぐことができる。  

## プルリクエスト
GitHub desktopのブランチで、右上にPull requestが表示される。
ブランチで行いたい作業が完了したらPull requestを押す。
「from master int hoge/hogehoge」に間違いが無ければ、
TitleやDescripitonを入力し、「Send pull request」を押す。
すると、プルリクエストが送信された状態になる。
プルリクエストを確認するには、ブラウザ上でGitHubにアクセスする必要がある。

## マージ

### 番外編
[MarkDown記法解説](http://qiita.com/tbpgr/items/989c6badefff69377da7)

# emoth

> **emoth: 感情ログアプリケーション**
>
> twitter, facebook, instagramなどの各種SNSのアカウントと連携してユーザの感情を見える化することができる。
>
> 画像認識を用いてユーザの顔から表情を抽出、感情を可視化する
>
> 自然言語処理を用いてユーザの発言から感情を抽出する
>
> いいね数の解析をしてユーザの心理状態に結びつける
>
> etc... アイディアはこれから出していこう


## 開発する上でのルール:pencil2:

①issueにやること・やりたいことを記入する。

②記入済みのissueから好きなものを選んで自分にassginする。

③pull request（PR）を立てて作業を行う。PR名の頭には作業中を表す[WIP]を付けること。

④reviewは必ず担当者以外の他者が行う。（reviewしないとmergeできないようにしている）

⑤reviewした人がマージを行う。ブランチの削除も合わせて行う。

## ブランチのルール:octocat:

①各開発者はmasterブランチからfeature branchを切ってから作業を行う。

②githubのリポジトリにpushしたら必ずPull Request（以下PR）を立てる。

③PRは必ず自分にAssignすること。

④Reviewerは特に選ばなくてもいいがみんながソースを見る文化を作ろう。


## デプロイ環境:floppy_disk:

heroku ステージング環境

https://emoth.herokuapp.com

masteブランチにマージされたタイミングで自動デプロイされるようになっています。


heroku ログインはこちらから

https://dashboard.heroku.com/apps/emoth

heroku review appを使うことでPRごとに
テスト環境を構築することができる。

そのうちEC2に環境を作りたいなぁ

## 開発環境

まずは[Cloud9](https://c9.io/)とか使ったらいいんじゃないかな？

慣れてきた or Cloud9嫌い！ってなったら各自ローカルに環境作ってやったらいいと思います。

## masterの最新版を取り込んだら…

ローカルのDDLを最新化

```
$ rails db:migarte
```

もしかしたら新しいgemも入ってるかもしれないので

```
$ bundle install
```

もしておこう。


## その他

どんなに忙しくても１週間に１分でも何かしらやってみよう

・１分あればissueやPRにコメントができる！

・５分あればdotinstallの動画が２つも見れる！

・１０分あればModel, View, Controllerの雛形だけでも作れる！


**〜３０分あればなんでもできる気になってきませんか？〜**

-----------------------------

以下、随時更新すること

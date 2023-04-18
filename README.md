# README

## 環境構築
```
$ bundle install --without=production
$ bin/rails db:setup
$ yarn install
$ bin/webpack
$ bin/rails s
```

## 事業をエンジニアリングしよう提案編の回答は以下に記述してください
選択した事業側の課題
直近一年間で、2回以上もくもく会に参加してくれた人は利用者全体の1%のみ。もくもく会で気の合う仲間を見つけられなかったのではないか？

提案内容
気の合う仲間を見つけるために、もくもく会に参加する人達がどういう人達なのかを事前に知ることができれば良い。
こうすれば、共通の趣味などを持った人達で集まることができ、モクモク会終了後の自己紹介やフリートークの時間に盛り上がって仲良くなったり、その流れで飲み会に行くなどの行動につながる可能性も出てくる。

実装方針
1. 既存のモクモク会アプリだと、プロフィールの欄が名前とEメールの欄しか無いので、プロフィール欄に自己紹介の欄、introductionを追加する。ここに、趣味とか最近気になったことなどを書いてもらう

2. プロフィール欄に自分自身のSNS（LINE, twitterなど）のIDを記入するIDの欄を追加する。

3. 複数のSNSのを使っている人のために、複数のSNSのIDを追加できるようにする。

4. 既存のモクモク会のアプリだと、参加者情報の部分をクリックできないので、参加者の名前をクリックして、その人のプロフィールに移動できるようにして、趣味などの情報を知ることができるようにする。

###  新機能を実装することで、期待される結果
こうすることで、モクモク会に参加する前に共通の趣味などを持った人が参加するかどうかを事前に知ることができる。また、気になる人がいれば、IDの欄に書いてある情報を使って、相手のSNSのアカウントを追加したりフォローしたりしてSNSで直接やり取りできるようにすることで、参加する前からある程度仲良くなってもらうことができる。




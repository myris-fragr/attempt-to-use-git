# attempt-to-use-git

## 概要

こんにちは。

今回は、私が文章を書くときに利用している便利なツールを紹介していきます。

その名も「git」です。


## なぜgit？

gitはテキストを扱う上でめっちゃ便利です。もう能率が上がること間違いありません。言いすぎたかな。まあ人によってはかなり便利です。

ゲームのセーブデータを想像してみてください。あんな感じに幾つもの履歴やバージョンを管理できたら便利だと思いませんか？

過去の編集状態をいつでも呼び出せて、採用されなかったバージョンをながめ、分岐を作って新しい文章を書くこともできます。

また、Githubなどのサービスを利用してリモートの環境を作れば、複数の端末から編集できたり、チームで作業できたりもします。


## やること

今回は簡単な使い方だけをご紹介しましょう。


### 作業を始める

まず作業スペースを作ります。これを「リポジトリ」と言います。

私はスマホやPCなどいくつもの端末から作業をしたいので、Githubを利用して「リモートリポジトリ」を作ります。

Githubにアクセスしてアカウントを作りましょう。

https://github.co.jp/

アカウント作成の説明は今回は端折っていきます。

1. https://github.com/ にアクセスします。
2. 右上のアイコンを押したらメニューが出ます。
3. 「Your Repositories」を押すと自分のリポジトリ一覧が表示されます。まだ何もないはずです。
4. 緑色の「New」ボタンを押して「Create a new repository」画面を開きます。
5. 「Repository name」に新しいリポジトリの名前を入力しましょう。
6. 「Public」か「Private」を選ぶことができます。作業を公開する意図がなければ「Private」がいいでしょう。
7. 「README」ファイルがあると便利なので、今回は「Add a README file」にチェックを付けておきましょう。
8. 「Create Repositorie」ボタンを押して完了です。


### 編集する

README.mdファイルを編集してみましょう。

おっと、その前にmdファイルについて説明しておかなければなりませんね。

マークダウンテキスト、略してmdです。

モノとしては純然たるプレーンテキストファイルなのですが、書類をつくったりHTMLやPDFに変換したり図を書いたり画像を載せたり、なにかと小回りの利く便利な奴です。Githubにおいては、書類は全部これで作ります。

最近はデジタル庁などのお役所でも使われることがあるようです。

簡単な書式を紹介しておきます。

```md

# 見出し

## 小さい見出し

- 箇条書き
- 箇条書き

1. 番号付き箇条書き
2. 番号付き箇条書き

```

こんな感じで、メモ感覚で書式を指定できます。楽でよいです。

では、鉛筆のボタンがあると思います。おなじみ編集ボタンですね。押すと編集画面が出ます。思い思いのことを書き連ねてみましょう。

ちなみにですが、お手持ちのPCやスマホにgitが使える環境を用意すれば、お使いの好きなエディタを使って編集することができます。ただ、長くなるので今回は説明しません。


### 変更を記録する

さて、作業はひと段落したでしょうか。

では、ゲームで言うところのセーブ、「コミット」を行いましょう。

1. 緑色の「Commit changes...」ボタンを押してみましょう。
2. あとから変更履歴を見直す時に便利な「Commit message」を書きます。今回ははじめから書き込まれているので、いいやと思ったらやんなくていいです。
3. どんな作業だったか説明を書いておく「Extended description」を、必要なら書きます。これは任意です。
4. 「Commit changes」ボタンを押して、作業を保存しましょう。

### 問題を提起する

自分の文章を眺めていると、改善しなければいけない点がいくつも出てきます。

一つずつ問題を見つけて、改善していきましょう。

ここでは問題のことを「issue」と呼びます。

1. 「issues」タブを開きます。
2. 「New issue」ボタンを押します。
3. 問題のタイトルを書きます。
4. 説明が必要なら書いておきます。
5. 「Submit new issue」を押して完了です。


### 問題を解決する

問題に応じて作業をしていきます。

「変更を記録する」章の通り、作業をしては切りのいいところでコミットしていきます。

ただ、今回は問題を解決する特別な作業です。「Commit message」欄は「メッセージ #数字」の形式でissueの番号を書いておきましょう。

これでissueと変更履歴を紐づけることができます。

issue画面に行って変更履歴が追加されていることを確認してみましょう。

### 問題を閉じる

問題が解決したら、issueを閉じます。

1. 「issues」タブを開きます。
2. 下のほうに「Close issue」ボタンがあります。これを押して、issueを完了させます。


## まとめ

gitというか、Githubの説明になってしまいました。

今回は文書きのためのgitということで、問題提起の方法など私が良く使う機能について紹介しました。

gitにはまだまだ便利な機能がたくさんあります。

- 編集履歴ごとの差分を表示する機能
- 過去の履歴を召喚する方法
- 変更履歴に分岐を作る方法（複数人で作業するとき便利です）
- 分岐を一つにまとめる方法

などなどです。

あと今回は紹介しませんでしたが、PCやスマホにgit環境を用意すると便利です。

PCではGithub DesktopやTortoise gitなどのGUIつきソフトが出回っています。スマホではObsidianが便利です。なにせ無料。

簡単と言ったら嘘にはなりますが、文書きがgitを使えるようになったら楽しい世の中になりそうだ、などと考えています。

みんなも使ってみてね！

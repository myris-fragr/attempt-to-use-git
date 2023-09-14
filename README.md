# attempt-to-use-git

## 概要

こんにちは。

今回は、私が文章を書くときに利用している便利なツールを紹介していきます。

その名も「git」です。

## なぜgit？

gitはテキストを扱う上でめっちゃ便利です。

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

1. 右上のアイコンを押したらメニューが出ます。
2. 「Your Repositories」を押すと自分のリポジトリ一覧が表示されます。まだ何もないはずです。
3. 緑色の「New」ボタンを押して新しいリポジトリ作成画面を開きます。
4. 「Create a new repository」画面になったでしょうか。そこで、
  1. 「Repository name」に新しいリポジトリの名前を入力しましょう。
  2. 「Public」か「Private」を選ぶことができます。作業を公開する意図がなければ「Private」がいいでしょう。
  3. 「README」ファイルがあると便利なので、今回は「Add a README file」にチェックを付けておきましょう。
5. 「Create Repositorie」ボタンを押して完了です。

### 編集する

README.mdファイルを編集してみましょう。

おっと、その前にmdファイルについて説明しておかなければなりませんね。

マークダウンテキスト、略してmdです。

モノとしては純然たるテキストファイルなのですが、書類をつくったりHTMLやPDFに変換したり図を書いたり画像を載せたり、なにかと小回りの利く便利な奴です。Githubにおいては、書類は全部これで作ります。

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

ちなみにですが、お手持ちのPCやスマホにGitが使える環境を用意すれば、お使いの好きなエディタを使って編集することができます。ただ、長くなるので今回は説明しません。

私はObsidianを使っています。git連携機能があって便利です。


### 変更を記録する

さて、作業はひと段落したでしょうか。

では、ゲームで言うところのセーブ、「コミット」を行いましょう。

1. 緑色の「Commit changes...」ボタンを押してみましょう。
  2. あとから変更履歴を見直す時に便利な「Commit message」を書きます。今回ははじめから書き込まれているので、いいやと思ったらやんなくていいです。
  3. どんな作業だったか説明を書いておく「Extended description」を、必要なら書きます。これは任意です。
2. 「Commit changes」ボタンを押して、作業を保存しましょう。

### 問題を提起する

自分の文章を眺めていると、改善しなければいけない点がいくつも出てきます。

一つずつ問題を見つけて、改善していきましょう。

1. 「issues」タブを開きます。
2. 「New issue」ボタンを押します。
3. 問題のタイトルとその説明を書きます。
4. 「Submit new issue」を押して完了です。

### 問題を解決する

### 問題を閉じる

## まとめ

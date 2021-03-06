# 寄稿者の方へ

デジコン代表のおーじぇい（@920OJ）です。まずは、寄稿のご協力ありがとうございます。

今年の新入生は、感染症拡大の影響で、イレギュラーな事態に見舞われています。そうした不安を、新入生と在校生が「デジタルコンテンツ」で繋がることで、少しでも軽減する手助けになれたらな、という思いでこのプロジェクトをはじめました。さらに、これをオープンソースで公開することにより、今後の部の資産としても活用することが出来るのではないか、と考えております。

かつてない逆境の中で、新入生・在校生がチーム一丸となれば、必ず大きな力を生み出し、互いの成長にもつながるはずです。とてもお忙しい中恐縮ですが、どうぞ宜しくお願い致します。

2020年3月19日 大岩潤矢（おーじぇい・@920OJ）

---

## 書き方について

執筆作業は全てこのレポジトリ内で行います。まずは、このレポジトリを手元にcloneしてください。

```bash
git clone https://github.com/TCU-DC/training-2020.git
```

次に、執筆用のブランチを切って下さい。ブランチ名は任意の英数字にします。講座を表すものにすると良いでしょう。（例: 初心者のHTML講座の場合、「start-html」）

```bash
git checkout -b start-html
```

ブランチを移動したことを確認したら、mdファイルを格納するディレクトリを作成します。「docs」ディレクトリに、「ブランチ名」のディレクトリを作成してください。

```bash
mkdir docs/start-html
```

その中にmdファイルを作成していきます。ファイル名は、01.md、02.md、03.md……と、数字の連番にしてください。

詳しくは、実際に「start-html」ディレクトリに02まで作成してあるので、そちらの書き方を参考にして下さい。

コミット時は、コミットメッセージに以下のような接頭辞をつけるとわかりやすいかと思います。
- 追加: `[add]`
- 変更: `[update]`
- バグ修正: `[fix]`
- ファイル削除: `[remove]`

例:
```bash
git add .
git commit -m "[add]初心者ページを追加"
```

すべて書き終わったら、一度 @920OJ に連絡して下さい。校正をした後、プルリクからのマージをします。

## 体裁・フォーマットについて

Markdown形式です。GitHubのドキュメントに準じます。

[基本的な書き方とフォーマットの構文 - GitHubヘルプ](https://help.github.com/ja/github/writing-on-github/basic-writing-and-formatting-syntax)

### 書く上でのTips
- 「ですます調」等の文体は指定しません。親しみやすい文章を書いていただけると嬉しいです。
- 絵文字を使うとより柔らかくなりますが、使いすぎないように注意しましょう。🤔
- 適切な見出しをつけましょう。ひと目見てそのセクションで何をするのかということがわかるように！
- 画像はGitレポジトリにアップロードするのではなく、Imgurなどの外部サービスを使うか、GitHubのIssueにアップロードした画像を挿入して下さい。
参考リンク: [https://qiita.com/ROY_M/items/2c4feb5de05535441bc8](https://qiita.com/ROY_M/items/2c4feb5de05535441bc8)

## 締め切り
とりあえず4/1目処に2020年新入生用Webページを立ち上げたいと思います。そこにいくつか紹介をするので、できれば3月末までに書き上げてくださると嬉しいです。（間に合わない場合は後になっても大丈夫です。最終4月中旬頃を目指しています）

## 連絡先
おーじぇいまで連絡をお願いします。春休み期間中はずっと暇なので、いつでもDM返信できます。

```
Twitter: https://twitter.com/920oj
```
#noemoji

チャットワークには気持ちを表現するためにエモーティコンが実装されています。このエモーティコンという機能は気持ちを表現する場合には便利なのですが、場合によっては邪魔になることがあります。
特に、エンジニア同士でのサンプルコードの共有時に、意図せずコードの中にエモーティコンが表示されてコピペ出来なくなってしまいます。


###このExtensionは、現在開いているチャットワークのエモーティコンを無効化します。

具体的には、エモーティコンで利用している文字列をalt属性にしていされているimgタグをaltの中の文字列に置換しています。

## インストール方法

現在はChrome Web Storeで公開していないので、インストール方法がちょっと複雑です。

* noemoji.crx をダウンロードする。
* Chromeの拡張機能のページにcrxファイルをドラッグ＆ドロップする。
* インストールするか聞かれるのでインストールする。


## 使い方

該当のチャットワークのページを開いて、noemojiアイコンをクリックしてください。新しくエモーティコンが投稿されると復活するので必要であれば再度押してください。
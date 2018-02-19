Amazon Pay japan Developer Summit 2018 Sample
===========================================

今回のライブコードで使う、htmlになります。
index.htmlをベースにライブコードを進めていきますので、興味のある方は clone してみてください。

あと、index.htmlを動かすのに、web serverが必要になってきます。
セッションでは、php -S を使ってやります。Macであれば標準で使えるはずです。


## 動かし方

まずは、gitコマンドを使ってCloneしてください。

```

$ git clone git@github.com:johna1203/amazonpayjpmeetup01.git

```

PHP: Built-in web server を使って動かしてみます。
今回は、ポートは必ず8080にしてください。

```
$ cd amazonpayjpmeetup01

$ php -S 0.0.0.0:8080

```

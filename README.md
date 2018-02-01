# 書籍情報取得プログラム

PHPで書かれた書籍情報を取得するプログラムです。
書誌情報は[版元ドットコム](http://www.hanmoto.com/about_api)様のAPIから取得しています。

## 使い方
バーコードリーダがあることを前提としたプログラムですが、手入力にも対応しています。

### 書籍情報と価格等の情報
`$ php book_JAN.php` と実行して下さい。その後は表示の指示に従って下さい。

### APIを叩くだけ
`$ php ISBN_API.php <ISBN>` と実行して下さい。 タイトル・著者・出版社を取得して表示します。

# 最後に

本プログラムを使用した際に生じた不都合・不利益に対して当方は一切の責任を負いません。

# 課題

以下の基本操作を一通り習得したうえで、このリポジトリにある page1.html, page2.html, page3.html を書き換えて各自のリモートリポジトリにプッシュしなさい。
書き換え内容は、最低、page1 から page2, page3 へジャンプできるリンク構造となっていること。

# HTML のリンク構造

HTML では、\<a\> タグによって、リンク構造を記述する。基本的な使用方法は、href オプションに、リンク先のアドレスを記述する。

同じサーバの同じディレクトリ内にあるファイルを指定する場合：
```
<a href='next.html'>次のページ</a>
```

インターネット上の他の場所を指定する場合：
```
<a href='http://www.tama.ac.jp/'>多摩大学</a>
```

参照：
- [w3school の link の解説](https://www.w3schools.com/html/html_links.asp)
- [w3school の href の解説](https://www.w3schools.com/tags/att_a_href.asp)


# 表示確認

xampp が正しくインストールされ、apache がサーバとして動作していれば

http://localhost/各自のリポジトリ名/hello.html

で、このリポジトリの hello.html ファイルが表示されるはずである。今回の「各自のリポジトリ名」は、html-link-ユーザ名 のはずである。


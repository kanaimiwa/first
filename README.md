#実行方法、書き方

##実行方法

* jquery.com/downloadでjQueryのファイルをダウンロードする
* または、jquery.com/downloadでホストされているスクリプトを使う
* bodyのとタグの直前に読み込む
* jQueryを読み込んだ後に、スクリプトを書く

##セレクタとメソッド
基本的には、この2つを覚えていく

* セレクタ：処理対象となるDOM(Document Object Model)要素
* メソッド：処理
* メソッドチェーン：処理はつなげてかける
* スクリプトの書き方

``` $(document).ready(function(){
$('p').css('color', 'red');
//$('p')：セレクタ
//.css('color', 'red')：メソッド
});

//省略できる
$(function(){
$('p').css('color', 'red').hide('slow');
//.hide('slow')：メソッドをつなげて書いている部分。メソッドチェーン
});
```



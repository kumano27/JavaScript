## #2 はじめてのJavaScript  
参考：ドットインストール  
<https://dotinstall.com/lessons/basic_javascript_v2/26702>  

JavaScriptは <script> タグ内に記入する  
<body> タグ終了の直前に書くのが一般的  

コンソールに hello world! と出力するindex.html作成  


```html:index.html
<!DOCTYPE html>
<html lang="ja">
<head>
	<meta charset="utf-8">
	<title>JavaScriptの練習</title>
</head>
<body>
	<script>
		console.log("hello world!");
	</script>
</body>
</html>

```

Chromeでindex.htmlを開く  
真っ白な画面が表示されている  
JavaScriptで追記したのはコンソールへの出力なのでコンソールを確認する  

Chromeでコンソールを確認するには、Chromeページ内で右クリック > 検証を選択  
デベロッパーツールが起動する  
Console を押下すると hello world! と表示されている  


コメントの書き方  


```javascript
/*
	複数行にわたるコメントの場合
	============================
		こんなコメント
	============================
*/


// 一行コメント
```


文の終わりには ; を忘れずに付ける  


script自体を外部ファイルに書く方法もある  
以下に外部ファイル(myscript.js)参照を行うソースを記述する  



```html:index.html
<!DOCTYPE html>
<html lang="ja">
<head>
	<meta charset="utf-8">
	<title>JavaScriptの練習</title>
</head>
<body>
	<!-- 外部ファイル参照処理 -->
	<script src="myscript.js"></script>	<!-- JavaScriptファイルの拡張子は.js -->
	<script>
		console.log("hello world!");
	</script>
</body>
</html>
```


先にmyscript.jsの内容(hello from script)がコンソールに表示され、続けて hello world! が表示される  

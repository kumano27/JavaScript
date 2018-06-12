## #3 変数とデータ型  
参考：ドットインストール  
<https://dotinstall.com/lessons/basic_javascript_v2/26703>  

変数:データにつけるラベル  


宣言を行う(var)  
今回の例ではmsg(メッセージ)という変数を作成  


"hello world!" という文字列を割り当てる  
割り当てるには ** = ** キーを使用  
=は代入演算子  
数学的な用途(AとBが等しい)ではない(AにBを代入する)  

msgが色々な所で使えるようになる  
例)console.log()の中身をmsgにすると前回と同様の結果となる  

```html:index.html
<!DOCTYPE html>
<html lang="ja">
<head>
	<meta charset="utf-8">
	<title>JavaScriptの練習</title>
</head>
<body>
	<script>
		/*
			変数:データにつけるラベル
		*/
		var msg;
		msg = "hello world!";
		console.log(msg);
	</script>
</body>
</html>
```


変数の宣言と代入は以下のように一行で記述する事が可能  

```html
var msg ="hello world!";
```

複数の変数が存在する際に以下のように一気に記述する事も可能  

```html
var msg ="hello world!",
	x = 20,
	y = 10;
```


JavaScriptで使用できるデータ型
- 文字列  
- 数値  
- 真偽値(true or false)  
- オブジェクト  
	- 配列  
	- 関数  
	- 組み込みオブジェクト  
- undefined(定義されていない)  
- null(何もない)  


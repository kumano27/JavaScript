## #4 数値を使ってみよう  
<https://dotinstall.com/lessons/basic_javascript_v2/26704>  


扱える数値の種類  
- 整数値  
- 実数地  
- マイナス値  

演算子も使用可能  
- +(加算)  
- -(減算)  
- /(除算)  
- *(乗算)  
- %(余りを求める)  

代入を伴う演算子  

単項演算子  


まず変数xを用意し、計算を行う(10 × 2)  
計算結果はコンソールに出力  


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
			数値
				10
				2.5
				-2.5
			演算子
				+ - * / %
				+= 代入を伴う演算子
				++ -- 単項演算子
		*/
		var x;
		x = 10 * 2;	// 20
		console.log(x);
	</script>
</body>
</html>
```

違う計算も行ってみる  
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
			数値
				10
				2.5
				-2.5
			演算子
				+ - * / %
				+= 代入を伴う演算子
				++ -- 単項演算子
		*/
		var x;
		x = 10 * 2;	// 20
		x = 10 % 3;	// 1
		console.log(x);
	</script>
</body>
</html>
```

%は余りを求めるのでコンソールには1が表示される  

代入演算子を使う
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
			数値
				10
				2.5
				-2.5
			演算子
				+ - * / %
				+= 代入を伴う演算子
				++ -- 単項演算子
		*/
		var x;
		x = 10 * 2;	// 20
		x = 10 % 3;	// 1
		// x = x + 5;
		x += 5	// 6
		console.log(x);
	</script>
</body>
</html>
```

x = x + 5とx += 5は同様の処理  
乗算を行いたい場合は x = x * 5 、x *= 5とすれば良い  

単項演算子
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
			数値
				10
				2.5
				-2.5
			演算子
				+ - * / %
				+= 代入を伴う演算子
				++ -- 単項演算子
		*/
		var x;
		x = 10 * 2;	// 20
		x = 10 % 3;	// 1
		x += 5	// 6
		// x++;
		++x;	// 7
		console.log(x);
	</script>
</body>
</html>
```

単項演算子記述法はx++でも++xでも可  
xに1を足す  
x--も可  
xから1を引く  
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
			数値
				10
				2.5
				-2.5
			演算子
				+ - * / %
				+= 代入を伴う演算子
				++ -- 単項演算子
		*/
		var x;
		x = 10 * 2;	// 20
		x = 10 % 3;	// 1
		x += 5	// 6
		++x;	// 7
		--x;	// 6
		console.log(x);
	</script>
</body>
</html>
```

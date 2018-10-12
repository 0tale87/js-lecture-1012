# テクノロジー（藤原） 10/12課題

- テキストエディタ（Visual Studio Codeなど）でREADME.mdを開きます
- 下の欄（` ``` `で挟まれている部分）に、ChromeデベロッパーツールのConsoleで実行したログを丸ごとコピー＆ペーストしてください

```
var numA 1 ;
VM1492:1 Uncaught SyntaxError: Unexpected number
var numA = 1 ;
undefined
var numB = 2 ;
undefined
var numA = 2 ;
undefined
var numB = 2 ;
undefined
var numB = 3 ;
undefined
var numC = numA + numB;
undefined
console.log ( numC )
VM1591:1 5
undefined
var numD = numA * numB;
undefined
console.log ( numD )
VM1642:1 6
undefined
var numA = 1 ;
undefined
var numB = 2 ;
undefined
var boolC = numA ==numB ;
undefined
console.log(boolC);
VM1768:1 false
undefined
var bool
undefined
var boolD = numA < numB;
undefined
console.log ( numD );
VM1818:1 6
undefined
console.log ( boolD );
VM1851:1 true
undefined
var numA = 1;
undefined
var numB = "1"
undefined
console.assertlog
undefined
console.log( numA == numB)
VM1974:1 true
undefined
;
undefined
console.log( numA === numB);
VM2007:1 false
undefined
var strA = "吾輩は";
undefined
var strB = "猫である";
undefined
var strC = strA + strB;
undefined
console.log( strC);
VM2128:1 吾輩は猫である
undefined
console.log(strA === strB);
VM2226:1 false
undefined
var numA = 1;
undefined
if (numA===1){
    console.log("numA = 1");
}
VM2256:2 numA = 1
undefined
if (numA===2){
    console.log("numA = 2")
}
undefined
var numA = 3;
undefined
if (numA===1){
    console.log("numA = 1");
}else if{
VM2325:3 Uncaught SyntaxError: Unexpected token {
if (numA===1){
    console.log("numA = 1");
} else if (numA === 2){
    console.log("numA = 2");
} else if (numA === 3){
    console.log("numA = 3");
} else {
    console.log("numA ≠ 1 or 2 or 3");
}
VM2671:6 numA = 3
undefined
var numA = 3;
undefined
if (numA%2==0){
    console.log("numA は偶数");
    if (numA >= 2){
        console.log("numAは2以上");
    }else{
        console.log("numAは2未満");
    }
}
undefined
if (numA%2==0){
    console.log("numA は偶数");
    if (numA >= 2){
        console.log("numAは2以上");
    }else{
        console.log("numAは2未満");
    }
}else{
    console.log("numAは奇数");
    if (numA >= 3){
        console.log("numAは3以上")l
VM3034:11 Uncaught SyntaxError: Unexpected identifier
if (numA%2==0){
    console.log("numA は偶数");
    if (numA >= 2){
        console.log("numAは2以上");
    }else{
        console.log("numAは2未満");
    }
}else{
    console.log("numAは奇数");
    if (numA >= 3){
        console.log("numAは3以上");
    }else{
        console.log("numAは3未満");
    }
}
VM3117:9 numAは奇数
VM3117:11 numAは3以上
undefined
```

## 例（下記の書き方をまねてください）

```
console.log('hello')
VM31:1 hello
undefined
```

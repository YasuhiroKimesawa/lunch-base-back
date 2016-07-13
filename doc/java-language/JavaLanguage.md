# VBSやPHPとの違い
## コンパイル型言語

- インタプリタ・・・実行時にプログラム文を1文ずつ機械語に変換していく。基本低速。  
  
- コンパイル・・・実行する前にソースコードを機械語に変換。実行時には、変換済みの機械語を実行する。基本高速。

VBSやPHP言語はインタプリタ型言語に近く(厳密には少し異なる)、  
javaはコンパイル型言語に近い(実際には機械語ではなくJava仮想マシンによってJavaバイトコードに変換され、  
実行時にはJavaバイトコードがインタプリタっぽく動作して実行される。これはLinux/Win/Macなど様々な環境で  
javaを実行するための仕組み)  

## 型がある

javaには変数の取りうる値を制限するため、全ての変数に型が必要。  
基本はクラス定義された型を使用するがjavaでは他にint, long, double, boolean などの基本データ型が用意されている
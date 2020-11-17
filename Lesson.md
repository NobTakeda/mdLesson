# Hello


hoge
huga  
piyo

そのまま改行すると横並びになるが、半角スペースを２つ挟むと改行される。
空行をつければ改行となる。

これは`インライン表示です`（バッククォートで`囲む`)

タグの埋め込みは```で囲む。java:で後ろにファイル名記入でソースコードがハイライトされるようになる。
```java:hoge.java
public class hoge{
   public static void main(String[] args){
      System.out.println("Hello");
   }
}
```


> これは引用です  
> 引用
>> 引用の引用  


*,-,_どれかを３つ並べると水平線となる。  
***
---
___

-,+,*でulタグの代わりになる

- リスト1  
- リスト２

1. 番号付きリスト1
2. 番号付きリスト２

< />で囲むとリンクになる
<htpps://www.google.co.jp/>  
[ ]( /)で[]の文字にリンク埋め込み  
[google](https://www.google.co.jp/)

強調表示  
こんにちは、今日も *元気に* **頑張り** ましょう。 ***more strong***  

!(https://joytas.net/php/man.jpg)  
![画像](https://joytas.net/php/man.jpg)  
持ち込みの画像はIssueにドラッグ＆ドロップ  
![float1](https://user-images.githubusercontent.com/73978266/99324913-89726080-28b8-11eb-92b0-dca7bfcffeac.jpg)  
<img src=https://user-images.githubusercontent.com/73978266/99324913-89726080-28b8-11eb-92b0-dca7bfcffeac.jpg width="100">

| 左揃え | 中央揃え | 右揃え |
|:---|:---:|---:|
|1 |2 |3 |
|4 |5 |6 |

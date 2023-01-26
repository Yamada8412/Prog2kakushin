### プログラム一覧

+ [work1](https://github.com/Yamada8412/Prog2kakushin/blob/main/work1.ipynb) (辞書攻撃に用いられる辞書を用いて、パスワード強度判定プログラムを作る.)
+ [work2](https://github.com/Yamada8412/Prog2kakushin/blob/main/work2.ipynb)(楕円の中で球を打ち、楕円内を20回反射したときの軌跡を描くプログラムを作成する.)
  + [work2のコードの説明と改訂版を紹介をした記事をQiitaに投稿しました](https://qiita.com/eirian0958/items/ee58bf4c6870e2d0c366) (**work2に関しては、こっちを見てください**)
+ [work3](https://github.com/Yamada8412/Prog2kakushin/blob/main/work3.ipynb) (Opencvでテンプレートマッチングを実装して、Amazonの商品画面から、その商品が現在在庫切れかを判断するプログラムを作成する.)

### プログラムの一部説明と注意事項
+ work1
  + パスワードの強度を計算するときに使われる数式や、判定に用いる条件は、Yamada8412が調整しながら適当に考えたもので、確率的・統計的に正しい計算式や条件に準拠していません.
  + 出力される判定結果は、基本的には、"強い"と返されやすいような計算式や判定となっています.

+ work2
  + Github上に上げているwork2のコードは、残念ながら時間に追われながら書いたので、とてもよろしくないコードになってしまいました.　コードの改訂版と数式の説明を[こちら](https://qiita.com/eirian0958/items/ee58bf4c6870e2d0c366) の方に書いたので、Githubのコードよりもぜひこっちを読んでみてください.
  
+ work3
  + [こちら](https://pystyle.info/opencv-template-matching/)で紹介されていたものを応用して、探索対象画面内にテンプレートの画像があるかないかを探索するプログラムになっています.
  + 今回、Yamada8412が作成したこのテンプレートマッチングのプログラムは、テンプレート画像が探索対象画面内になかった場合は、ほぼ機能しません.
  + このプログラムだけでは、あまり実用性がないと思うので、目的に合わせて他のプログラムと組み合わせて使ってみて下さい.

### 参考文献
+ [テンプレートマッチングの紹介](https://pystyle.info/opencv-template-matching/)

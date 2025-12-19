# robosys2025
2025ロボットシステム学 課題1

![test](https://github.com/TaikiAkiyama/kadai1/actions/workflows/test.yml/badge.svg)

## ナベアツコマンド
ナベアツコマンドは、数字nを標準入力から受け取り、1~nまでの間にある3の倍数と、3がつく数字を標準出力に表示するコマンドです。

## 謝辞


## インストール方法
- リポジトリをコピーしたいディレクトリでクローンしてください。
```
$ git clone https://github.com/TaikiAkiyama/robosys2025.git
```
- robosys2025に移動してください。
```
$ cd robosys2025
```
- 実行できます。
```
$ ./nabeatu
```

## 必要なソフトウェア
- Python
  - テスト済みバージョン: 3.7~3.12

## テスト環境
- Ubuntu 24.04.3 LTS

## 使い方
実行したらを数字nを入力してください
```
$ ./nabeatu
13
```

ctrl + D かEnterを押すと3の倍数と3のついた数字が表示されます。
```
$ ./nabeatu
13
3
6
9
12
13
```
実行例
 - 単に該当する数字が何個含まれているかを確認したい場合は<span style="color:red">wc -l`</span>を使ってください。
```
$ ./nabeatu | wc -l
13
5
```

## ライセンス
- このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
- このパッケージのtestコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
    - [ryuichiueda/my_slides robosys_2025](https://github.com/ryuichiueda/slides_marp/blob/master/robosys2025/lesson6.md) 
- © 2025 Taiki Akiyama


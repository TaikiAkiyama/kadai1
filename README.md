# robosys2025
2025ロボットシステム学 課題1

![test](https://github.com/TaikiAkiyama/kadai1/actions/workflows/test.yml/badge.svg)

## funny_countコマンド 
funny_countコマンドは、数字nを標準入力から受け取り、1~nまでの間にある3の倍数と3を含む数字を標準出力に表示するコマンドです。

## 謝辞
funny_countコマンドはコメディアンである桂三度(世界のナベアツ)氏のネタ「3の倍数と3を含む数字の時だけアホになる」にインスパイアされて作成されました。

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
$ ./funny_count
```

## 必要なソフトウェア
- Python
  - テスト済みバージョン: 3.7~3.12

## テスト環境
- Ubuntu 24.04.3 LTS

## 使い方
- 実行すると、1から入力された数字(今回は13)までの間にある、3の倍数と3を含む数字が表示されます。
```
$ echo 13 | ./funny_count
3
6
9
12
13
```
- 該当する数字が何個含まれているかを確認したい場合は`wc -l`を使ってください。
```
$ echo 13 | ./funny_count | wc -l
5
```

## ライセンス
- このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
- このパッケージのtestコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
    - [ryuichiueda/my_slides robosys_2025](https://github.com/ryuichiueda/slides_marp/blob/master/robosys2025/lesson6.md) 
- © 2025 Taiki Akiyama


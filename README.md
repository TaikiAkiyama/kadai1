# kadai1
2025ロボットシステム学

![test](https://github.com/TaikiAkiyama/kadai1/actions/workflows/test.yml/badge.svg)

## 統計コマンド
概要
calcコマンドは、標準入力から受け取った統計データの合計、最大、最小、平均、個数を計算し、計算結果を標準出力に表示するコマンドです。

## 必要なソフトウェア
- Python
  - テスト済みバージョン: 3.7~3.12

## テスト環境
- Ubuntu 24.04.3 LTS

## 実行方法
- 以下のコマンドで実行します。

```

$ seq 5 | ./calc sum
15
```

- 操作ガイド
  - sum:合計
  - max:最大
  - min:最小
  - avg:平均
  - count:個数

## ライセンス
- このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
- このパッケージのtestコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
    -[ryuichiueda/my_slides robosys_2025](https://github.com/ryuichiueda/slides_marp/blob/master/robosys2025/lesson6.md) 
- © 2025 Taiki Akiyama


# 挿入ソート

## 概要

挿入ソートは、ソート済みの部分リストを作成しながら、未ソートの部分リストをソートしていくアルゴリズムである。

## 計算量

- 最悪時間計算量: $O(n^2)$
- 平均時間計算量: $O(n^2)$
- 最良時間計算量: $O(n)$
- 最悪空間計算量: $O(1)$
- 安定ソート: Yes

## アルゴリズム

挿入ソートのアルゴリズムは以下の通り。

1. ソート済みの部分リストを作成する。
2. 未ソートの部分リストの先頭から要素を取り出し、ソート済みの部分リストに挿入する。
3. 未ソートの部分リストが空になるまで 2 を繰り返す。
4. ソート済みの部分リストが完成する。

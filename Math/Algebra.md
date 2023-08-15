# [代数学](https://ja.wikipedia.org/wiki/%E4%BB%A3%E6%95%B0%E5%AD%A6)

数の代わりに文字を用いて方程式の解法などを研究する。

## [テンソル (tensor)](https://ja.wikipedia.org/wiki/%E3%83%86%E3%83%B3%E3%82%BD%E3%83%AB)

線形的な量または線形的な幾何概念を一般化した表現。

ex.

- 0次元 -> スカラー
- 1次元 -> ベクトル
- 2次元 -> 行列
- 3次元 -> 3×3×3 テンソル

### 階数

対応する量を表すのに必要な配列の添字の組の数。

## [スカラー (Scalar)](https://ja.wikipedia.org/wiki/%E3%82%B9%E3%82%AB%E3%83%A9%E3%83%BC_(%E6%95%B0%E5%AD%A6))

大きさを持ち、向きを持たない量。

- ベクトルに対比するものとしての実数である。

## [ベクトル (Vector)](https://ja.wikipedia.org/wiki/%E3%83%99%E3%82%AF%E3%83%88%E3%83%AB)

大きさと向きを持つ量。

- ベクトル空間の元。
- 線形性を持つ。
- 和とスカラー倍を取る事ができる量

## [行列 (matrix)](./Matrix.md) 

詳細はリンク先に。

## [写像(mapping)](https://ja.wikipedia.org/wiki/%E5%86%99%E5%83%8F)

A の要素全てにおいて，B の要素をただ一つ返す。

- 関数、変換、作用素、射などが同義語である。
- A の違う要素に対して，Bの同じ要素を返してもよい，
- A の要素と対応付けされない B の要素があってもよい。
- B の要素であれば，どの要素を返してもよい。
- A を定義域と言う。
- B を終域と言う。
- B で値をとる域を値域と言う。

### [単射 (injection)](https://ja.wikipedia.org/wiki/%E5%8D%98%E5%B0%84)

2つ以上の要素が対応付かない。

- 単写とも言う。
- 1対1である。

### [全射 (surjection)](https://ja.wikipedia.org/wiki/%E5%85%A8%E5%B0%84)

全ての要素が対応付けられる。

- 全写とも言う。
- 終域と値域が同一である。

### [全単射 (bijection)](https://ja.wikipedia.org/wiki/%E5%85%A8%E5%8D%98%E5%B0%84)

単射かつ全射である。

- 双射とも言う。
- 可逆である。
- 逆関数(逆写像)が定義できる。

## [逆写像 (inverse mapping)](https://ja.wikipedia.org/wiki/%E9%80%86%E5%86%99%E5%83%8F)

写像の与える元の対応関係を「反対」にして得られる写像である。

- 全単射となる。

## [恒等写像 (identity mapping)](https://ja.wikipedia.org/wiki/%E6%81%92%E7%AD%89%E5%86%99%E5%83%8F)

同じ値を常にそのまま返す写像である。

- 定義域および終域が同一である。

### [線形写像 (linear mapping)](https://ja.wikipedia.org/wiki/%E7%B7%9A%E5%9E%8B%E5%86%99%E5%83%8F)

ベクトル空間の和と定数倍が保存される写像である。

- 以下が成立する。
  - f(x+y)=f(x)+f(y)
  - f(kx)=kf(x)

### [多重線型写像](https://ja.wikipedia.org/wiki/%E5%A4%9A%E9%87%8D%E7%B7%9A%E5%9E%8B%E5%86%99%E5%83%8F)

- TODO

## [ガウスの消去法(Gaussian elimination)](https://ja.wikipedia.org/wiki/%E3%82%AC%E3%82%A6%E3%82%B9%E3%81%AE%E6%B6%88%E5%8E%BB%E6%B3%95)

- 掃き出し法とも言う。
- 2つのステップから成る
  - 前進消去 (forward elimination) 
  - 後退代入 (backward substitution) 
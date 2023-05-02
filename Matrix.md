## [行列](https://ja.wikipedia.org/wiki/%E8%A1%8C%E5%88%97)

- 数や記号や式などを縦と横に矩形状に配列したものである。
- 横に並んだ一筋を行(row)、縦に並んだ一筋を列(column)と呼ぶ。

```mermaid
flowchart TD
    matrix["行列"]
    square["正方行列(A)"]
    symmetric["対称行列"]
    antiSymmetric["交代行列"]

    transpose["転置行列(tA)"]
    orthogonal["直行行列"]
    complexConjugate["複素共役行列(A‾)"]
    adjoint["随伴行列(A†)"]
    hermitian["エルミート行列"]
    unitary["ユニタリ行列"]

    matrix --"行要素数=列要素数"--> square
    square --転置--> transpose
    transpose --"tA=A"--> symmetric
    transpose --"tA=−A"--> antiSymmetric
    transpose --"tA=A^−1"--> orthogonal
    square --複素共役--> complexConjugate
    transpose --複素共役--> adjoint
    complexConjugate --転置--> adjoint
    adjoint --"A†=A"--> hermitian
    adjoint --"A†=A^−1"--> unitary
```

## [正方行列](https://ja.wikipedia.org/wiki/%E6%AD%A3%E6%96%B9%E8%A1%8C%E5%88%97)

- 行要素の数と列要素の数が一致する。

## [転置行列](https://ja.wikipedia.org/wiki/%E8%BB%A2%E7%BD%AE%E8%A1%8C%E5%88%97)

- 要素を入れ替えてできる。
 
## [対称行列](https://ja.wikipedia.org/wiki/%E5%AF%BE%E7%A7%B0%E8%A1%8C%E5%88%97)

- 正方行列である。
- 自身の転置行列と一致する。
- 転置に対して対称性を持つ。

## [交代行列](https://ja.wikipedia.org/wiki/%E4%BA%A4%E4%BB%A3%E8%A1%8C%E5%88%97)

- 歪対称行列（skew-symmetric matrix）とも言う。
- 反対称行列（antisymmetric matrix）とも言う。
- 正方行列である。
- 転置行列が自身の −1 倍となる。
- 転置に対して反対称性を持つ。

## [正規行列](https://ja.wikipedia.org/wiki/%E6%AD%A3%E8%A6%8F%E8%A1%8C%E5%88%97)

- 複素数に成分をとる。
- 正方行列である。
 
## [正則行列](https://ja.wikipedia.org/wiki/%E6%AD%A3%E5%89%87%E8%A1%8C%E5%88%97)

- 非特異行列とも言う。
- 可逆行列とも言う。
- 正方行列である。
- 通常の積に関する逆元を持つ。

## 逆行列

## [直交行列](https://ja.wikipedia.org/wiki/%E7%9B%B4%E4%BA%A4%E8%A1%8C%E5%88%97)

- 転置行列と逆行列が等しい。
- 正方行列である。
- 正則行列である。

### 反射行列

### 回転行列

### 置換行列

## 複素共役行列

- すべての成分の共役複素数を成分とする。

## ユニタリ行列

- 正方行列である。
- 正規行列である。
- 直交行列を複素数体へ拡張した。

## [随伴行列](https://ja.wikipedia.org/wiki/%E9%9A%8F%E4%BC%B4%E8%A1%8C%E5%88%97)

- エルミート転置 (Hermitian transpose)とも言う。
- エルミート共軛 (Hermitian conjugate)とも言う。
- エルミート随伴 (Hermitian adjoint) とも言う。

## [エルミート行列](https://ja.wikipedia.org/wiki/%E3%83%A6%E3%83%8B%E3%82%BF%E3%83%AA%E8%A1%8C%E5%88%97)

- 自己随伴行列（self-adjoint matrix）とも言う。
- 複素数に成分をとる正方行列である。
- 自身の随伴行列（共軛転置）と一致する。

## 単位行列

- 複素数を成分とする。

## 複素行列

## [逆元](https://ja.wikipedia.org/wiki/%E9%80%86%E5%85%83)

- 数の加法に対する反数や乗法に関する逆数の概念の一般化である。
- 与えられた元に結合してその効果を「打ち消す」効果を持つ元のことである。

## [共役/共軛](https://ja.wikipedia.org/wiki/%E5%85%B1%E5%BD%B9)

- 2つのものがセットになって結びついている。
- 同様の働きをする。

### [複素共役](https://ja.wikipedia.org/wiki/%E8%A4%87%E7%B4%A0%E5%85%B1%E5%BD%B9)

- 複素数の虚部を反数にした複素数をとる。


## [行列式](https://ja.wikipedia.org/wiki/%E8%A1%8C%E5%88%97%E5%BC%8F)

- 正方行列に対して定義される。
- 線型変換に対して線形空間の拡大率と言える。

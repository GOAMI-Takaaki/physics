# [数学 (Mathematics)](https://ja.wikipedia.org/wiki/%E6%95%B0%E5%AD%A6)

## [冪乗（exponentiation）](https://ja.wikipedia.org/wiki/%E5%86%AA%E4%B9%97)

x を n 回掛け合わせた数である。

- x^n
- x を底（base）もしくは基数と呼ぶ。
- n を冪数、冪指数または指数 (exponent) と呼ぶ。
- 累乗は n が自然数（正の整数）に限定される。

ex.

- 2^2 = 4
- 2^1 = 2
- 2^0 = 1
- 2^-1 = 1/2
- 1^-2 = 1/4

## [対数 (Logarithm)](https://ja.wikipedia.org/wiki/%E5%AF%BE%E6%95%B0)


「aを何乗したらbになるか」を表す数である。

- X=log a b
- a^x=b

ex. 

- log 2 4=2
- log 2 2=1
- log 2 1=0
- log 2 1/2=-1
- log 2 1/4=-2

## [虚数単位 (imaginary unit)](https://ja.wikipedia.org/wiki/%E8%99%9A%E6%95%B0%E5%8D%98%E4%BD%8D)

2乗して −1 になる数のことである。

- i^2=-1
- i=√-1
- i は実数でない。

## [複素数 (complex number)](https://ja.wikipedia.org/wiki/%E8%A4%87%E7%B4%A0%E6%95%B0)

2つの実数 a, b と虚数単位 i を用いて表す数である。

- z = a + bi

### [共役・共軛複素数（complex conjugate number）](https://ja.wikipedia.org/wiki/%E8%A4%87%E7%B4%A0%E5%85%B1%E5%BD%B9)

虚部 b を反数にした複素数である。

- z¯ = a − bi

## [微積分 (calculus)](https://ja.wikipedia.org/wiki/%E5%BE%AE%E5%88%86%E7%A9%8D%E5%88%86%E5%AD%A6)

### [微分 (differential)](https://ja.wikipedia.org/wiki/%E5%BE%AE%E5%88%86)

ある関数のある地点における接線の傾きである。

- lim h->0 [f(x+h)-f(x)]/h
- 瞬間の変化率と言える。
- 導関数 
  - y=c -> y′=0
  - y=xn -> y′=nx^n−1

ex. 

- f(x)=2x^2
- f'(x)
  - =lim h->0 [2(x+h)^2-2x^2]/h
  - =lim h->0 [2x^2+4xh+h^2-2x^2]/h
  - =lim h->0 [4xh+h^2]/h
  - =lim h->0 [4x+h]
  - =4x
- f'(x)
  - =2\*2x^(2-1)
  - =4x

### [積分 (integral)](https://ja.wikipedia.org/wiki/%E7%A9%8D%E5%88%86%E6%B3%95)

ある関数が描く面積である。

#### 不定積分

微分すると関数f(x) になる。

- Cは積分定数である。

ex.

- f(x)=4x
- f'(x)
  - =2\*x^(1+1)
  - =2\*x^2+C

#### 定積分

不定積分に積分区間の両端の値を代入した値の差である。
 
- ∫a-b f(x)dx
- ∫: インテグラル

ex.

- f(x)=4x
- a-b:1-2
- ∫a-b f(x)dx
  - =∫1-2 4xdx
  - =∫1-2 2x^2
  - = 2\*2^2-2\*1^2
  - = 8-4
  - = 4

## 参考

- [LaTeX/Mathematics](https://en.wikibooks.org/wiki/LaTeX/Mathematics)

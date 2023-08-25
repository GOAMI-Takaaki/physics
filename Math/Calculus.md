# [微積分 (Calculus)](https://ja.wikipedia.org/wiki/%E5%BE%AE%E5%88%86%E7%A9%8D%E5%88%86%E5%AD%A6)

## [微分 (Differential)](https://ja.wikipedia.org/wiki/%E5%BE%AE%E5%88%86)

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

## [積分 (integral)](https://ja.wikipedia.org/wiki/%E7%A9%8D%E5%88%86%E6%B3%95)

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

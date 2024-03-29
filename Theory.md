# 理論

```mermaid
stateDiagram-v2
    state 第1相転移[10^-44秒後,10^33K] {
        state 第2相転移[10^-36秒後,10^28K] {
            state 第3相転移[10^-11秒後,10^16K] {

                state 電磁気力 {
                    state "電気" as el
                    state "磁気" as ma
                    state "古典電磁気学\n(マックスウェル)" as f
                    state "量子電磁力学(QED)" as qe
                }

                state 弱い力 {
                    state "β崩壊" as b
                    state "弱い力\n(フェルミ)" as w
                }
                state "電弱統一理論\n[ワインバーグ・サラム理論]" as fw
            }

            state 強い力 {
                state "原子核" as at
                state "強い力\n(湯川)" as gl
                state "量子色力学(QCD)" as qc
            }

            state "大統一理論\n[超対称性理論]" as fwgl
        }

        state 重力 {
            state "地上重力\n(ガリレオ)" as mo
            state "天体重力\n[ケプラーの法則]" as as
            state "万有引力\n(ニュートン)" as ug
            state "重力\n[一般相対性理論]\n(アインシュタイン)" as gr
            
            state "量子重力\n(未完成)" as qgr
        }
        state "超大統一理論\n[超弦理論？]" as fwglr
    }
    state "万物の理論" as toe

    el --> f
    ma --> f
    f --> qe
    qe --> fw
    b --> w
    w --> fw
    fw --> fwgl
    at --> gl
    gl --> qc
    qc --> fwgl
    fwgl --> fwglr
    mo --> ug
    as --> ug
    ug --> gr
    gr --> qgr
    qgr --> fwglr
    fwglr --> toe
```

## 電磁気力

### [電気](https://ja.wikipedia.org/wiki/%E9%9B%BB%E6%B0%97)

### [磁気](https://ja.wikipedia.org/wiki/%E7%A3%81%E6%80%A7)

### [古典電磁気学](https://ja.wikipedia.org/wiki/%E5%8F%A4%E5%85%B8%E9%9B%BB%E7%A3%81%E6%B0%97%E5%AD%A6)

### [電磁気学](https://ja.wikipedia.org/wiki/%E9%9B%BB%E7%A3%81%E6%B0%97%E5%AD%A6)

### [量子電磁力学](https://ja.wikipedia.org/wiki/%E9%87%8F%E5%AD%90%E9%9B%BB%E7%A3%81%E5%8A%9B%E5%AD%A6)

## 弱い力

### [ベータ崩壊](https://ja.wikipedia.org/wiki/%E3%83%99%E3%83%BC%E3%82%BF%E5%B4%A9%E5%A3%8A)

## 強い力

### [量子色力学](https://ja.wikipedia.org/wiki/%E9%87%8F%E5%AD%90%E8%89%B2%E5%8A%9B%E5%AD%A6)

## 重力

### [量子重力](https://ja.wikipedia.org/wiki/%E9%87%8F%E5%AD%90%E9%87%8D%E5%8A%9B%E7%90%86%E8%AB%96)

### [相対性理論](https://ja.wikipedia.org/wiki/%E7%9B%B8%E5%AF%BE%E6%80%A7%E7%90%86%E8%AB%96)

#### [特殊相対性理論](https://ja.wikipedia.org/wiki/%E7%89%B9%E6%AE%8A%E7%9B%B8%E5%AF%BE%E6%80%A7%E7%90%86%E8%AB%96)

#### [一般相対性理論](https://ja.wikipedia.org/wiki/%E4%B8%80%E8%88%AC%E7%9B%B8%E5%AF%BE%E6%80%A7%E7%90%86%E8%AB%96)

### [万有引力](https://ja.wikipedia.org/wiki/%E4%B8%87%E6%9C%89%E5%BC%95%E5%8A%9B)

### [ケプラーの法則](https://ja.wikipedia.org/wiki/%E3%82%B1%E3%83%97%E3%83%A9%E3%83%BC%E3%81%AE%E6%B3%95%E5%89%87)

## 統一理論

### [（グラショウ・）ワインバーグ・サラム理論](https://ja.wikipedia.org/wiki/%E3%83%AF%E3%82%A4%E3%83%B3%E3%83%90%E3%83%BC%E3%82%B0%EF%BC%9D%E3%82%B5%E3%83%A9%E3%83%A0%E7%90%86%E8%AB%96)

- 弱い相互作用と電磁相互作用を統一的に記述する電弱統一理論である。


### [超対称性理論](https://ja.wikipedia.org/wiki/%E8%B6%85%E5%AF%BE%E7%A7%B0%E6%80%A7%E7%90%86%E8%AB%96)

- 仮説である。
- 超対称性粒子の存在を想定する。
  - ボース粒子とフェルミ粒子の入れ替えに対応する。
  - 一部はダークマターの候補の一つである。
- 階層性問題を解決する。

### [超弦理論](https://ja.wikipedia.org/wiki/%E8%B6%85%E5%BC%A6%E7%90%86%E8%AB%96)

- 仮説である。
- 超ひも理論、スーパーストリング理論とも呼ばれる。
- 弦理論に、超対称性という考えを加え、拡張したもの。
- 5つの理論がある。
  - I型、IIA型、IIB型、ヘテロSO（32）、ヘテロE8×E8

#### [弦理論](https://ja.wikipedia.org/wiki/%E5%BC%A6%E7%90%86%E8%AB%96)

- 物質の最小単位を1次元の拡がりをもつ弦であると想定する。
- 弦の大きさはプランク長（10-35m）程度とする。
- 弦には「閉じた弦」と「開いた弦」の2種類がある。
- 発散の問題を解決する。
  - 大きさが無限に小さい0次元の点粒子の場合
    - 粒子間距離が0のとき、相互作用が無限大になってしまう。
  - 繰り込みが不要になった。
- 10次元時空を必要とする。
  - 我々が認識できない6次元は、コンパクト化される。
  - [カラビ・ヤウ多様体](https://ja.wikipedia.org/wiki/%E3%82%AB%E3%83%A9%E3%83%93%E3%83%BB%E3%83%A4%E3%82%A6%E5%A4%9A%E6%A7%98%E4%BD%93)の形をしている。

#### [M理論](https://ja.wikipedia.org/wiki/M%E7%90%86%E8%AB%96)

- 5つの超弦理論を統合する。
- 11次元（空間次元が10個、時間次元が1個）の仮説理論である。
- 2次元の膜（メンブレーン）や5次元の膜が構成要素である。
- 問題は、2次元の膜を量子化する方法が分からないことである。

### [万物の理論](https://ja.wikipedia.org/wiki/%E4%B8%87%E7%89%A9%E3%81%AE%E7%90%86%E8%AB%96)

- 自然界に存在する4つの力を統一的に記述する。
  - 電磁気力・弱い力・強い力・重力
- 素粒子のあらゆる性質を説明できる。
- 宇宙（時空間）が誕生し、消滅する様子を説明できる。

## その他

### [統一場理論](https://ja.wikipedia.org/wiki/%E7%B5%B1%E4%B8%80%E5%A0%B4%E7%90%86%E8%AB%96)

### [ニュートン力学](https://ja.wikipedia.org/wiki/%E3%83%8B%E3%83%A5%E3%83%BC%E3%83%88%E3%83%B3%E5%8A%9B%E5%AD%A6)

## 用語

### [階層性問題](https://ja.wikiped ia.org/wiki/%E9%9A%8E%E5%B1%A4%E6%80%A7%E5%95%8F%E9%A1%8C)

- 弱い力がなぜ重力に比べ1032も強いかという問いである。
- 場の量子論および繰り込みという手法の適用によって生じる。

### [繰り込み](https://ja.wikipedia.org/wiki/%E7%B9%B0%E3%82%8A%E8%BE%BC%E3%81%BF)

- 計算結果が無限大に発散してしまうのを防ぐ数学的な技法である。
- 場の量子論が満たすべき最重要な原理のひとつでもある。
- 電磁相互作用に適用した量子電磁力学が完成した。

### [摂動](https://ja.wikipedia.org/wiki/%E6%91%82%E5%8B%95)

- 主要な力の寄与（主要項）による運動が、他の副次的な力の寄与（摂動項）によって乱される現象である。
- 粒子の運動が複数粒子の間に相互作用が働くことによって乱れることも指す。

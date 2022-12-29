# 物理学

個人的な整理の為の覚書です。

```mermaid
C4Component

title 物質 と 相互作用

Container_Boundary(element, "元素") {
  Container_Boundary(atom, "原子") {
    Container_Boundary(atomicNucleus, "原子核") {
      Container_Boundary(nucleon, "核子") {
        Container_Boundary(proton, "陽子") {
          Container(protonUpTypeQuark1, "アップクォーク")
          Container(protonUpTypeQuark2, "アップクォーク")
          Container(protonDownTypeQuark1, "ダウンクォーク")
        }
        Container_Boundary(neutron, "中性子") {
          Container(neutonUpTypeQuark1, "アップクォーク")
          Container(neutonDownTypeQuark1, "ダウンクォーク1")
          Container(neutonDownTypeQuark2, "ダウンクォーク2")
        }
      }
      Container(atomElectron, "電子")
    }
  }
}
Rel(electron, atomElectron, "")

Rel(upQuark, protonUpTypeQuark1, "")
Rel(upQuark, protonUpTypeQuark2, "")
Rel(upQuark, neutonUpTypeQuark1, "")

Rel(downQuark, protonDownTypeQuark1, "")
Rel(downQuark, neutonDownTypeQuark1, "")
Rel(downQuark, neutonDownTypeQuark2, "")

Container_Boundary(hadron, "ハドロン") {
  Container_Boundary(baryon, "バリオン") {
    Container(baryonQuark1, "クォーク1")
    Container(baryonQuark2, "クォーク2")
    Container(baryonQuark3, "クォーク3")
  }
}

Container_Boundary(elementaryParticle, "素粒子") {
  Container_Boundary(fermion, "フェルミ粒子") {
    Container_Boundary(quark, "クォーク") {
      Container_Boundary(upTypeQuark, "上系列クォーク") {
        Container(upQuark, "アップクォーク（u）")
        Container(charmQuark, "チャームクォーク（c）")
        Container(topQuark, "トップクォーク（t）")
      }
      Container_Boundary(downTypeQuark, "下系列クォーク") {
        Container(downQuark, "ダウンクォーク（d）")
        Container(strangeQuark, "ストレンジクォーク（s）")
        Container(bottomQuark, "ボトムクォーク（b）")
      }
    }
    Container_Boundary(lepton, "レプトン") {
      Container_Boundary(chargedLepton, "荷電レプトン") {
        Container(electron, "電子 (e)")
        Container(muon, "ミュー粒子（μ）")
        Container(tauon, "タウ粒子（τ）")
      }
      Container_Boundary(downQuark, "ニュートリノ") {
        Container(electronNeutrino, "電子ニュートリノ（νe）")
        Container(muonNeutrino, "ミューニュートリノ（νμ）")
        Container(tauonNeutrino, "タウニュートリノ（ντ）")
      }
    }
  }
  Container_Boundary(boson, "ボース粒子") {
    Container_Boundary(gaugeBoson, "ゲージ粒子") {
      Container(gluon, "グルーオン")
      Container_Boundary(weakBoson, "ウィークボソン") {
        Container(wBoson, "Wボソン")
        Container(zBoson, "Zボソン")      
      }
      Container(photon, "光子")
      Container(graviton, "重力子")
    }
    Container_Boundary(scalarBoson, "スカラー粒子") {
      Container(higgsBoson , "ヒッグス粒子")
    }
  }
}

Rel(gluon, strongInteraction, "")
Rel(wBoson, weakInteraction, "")
Rel(zBoson, weakInteraction, "")
Rel(photon, electromagneticInteraction, "")
Rel(graviton, gravitationalInteraction, "")

Container_Boundary(fundamentalInteraction, "基本相互作用") {
  Container(strongInteraction, "強い相互作用")
  Container(weakInteraction, "弱い相互作用")
  Container(electromagneticInteraction, "電磁相互作用")
  Container(gravitationalInteraction, "重力相互作用")
}

```

- [物質](./Material.md)
- [相互作用](./Interaction.md)
- [理論](./Theory.md)

## TODO

- 元素の位置づけの見直し
- [粒子統計](https://ja.wikipedia.org/wiki/%E7%B2%92%E5%AD%90%E7%B5%B1%E8%A8%88)
- [スピン](https://ja.wikipedia.org/wiki/%E3%82%B9%E3%83%94%E3%83%B3%E8%A7%92%E9%81%8B%E5%8B%95%E9%87%8F)
- [世代](https://ja.wikipedia.org/wiki/%E4%B8%96%E4%BB%A3_(%E7%B4%A0%E7%B2%92%E5%AD%90))
- [電荷](https://ja.wikipedia.org/wiki/%E9%9B%BB%E8%8D%B7)
- [色荷](https://ja.wikipedia.org/wiki/%E8%89%B2%E8%8D%B7)
- [反粒子](https://ja.wikipedia.org/wiki/%E5%8F%8D%E7%B2%92%E5%AD%90)
- [バリオン数](https://ja.wikipedia.org/wiki/%E3%83%90%E3%83%AA%E3%82%AA%E3%83%B3%E6%95%B0)
- [中間子](https://ja.wikipedia.org/wiki/%E4%B8%AD%E9%96%93%E5%AD%90)
- [複合粒子](https://ja.wikipedia.org/wiki/%E8%A4%87%E5%90%88%E7%B2%92%E5%AD%90)
- [紐](https://en.wikipedia.org/wiki/String_(physics))


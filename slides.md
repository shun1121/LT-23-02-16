---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: slide-left
# use UnoCSS
css: unocss
---

# デスクワーク中の姿勢、<br>見直してみませんか？
Shunsuke Fukunishi

---
transition: fade-out
---

# 目次

- 背景
- 体の不調の原因①
- 体の不調の原因②
- 改善方法
- 実践していること
- 使用しているもの
- 参考

<style>
  ul {
    margin-top: 40px;
    font-size: 24px;
  }
</style>
---

# 背景

デスクワークの際、悪い姿勢で作業していたことで体の調子が悪くなった

<div class="flex">
  <div class="left">

  <v-clicks>

  - 肩こり

  - 背中の痛み

  - 吐き気

  </v-clicks>

  </div>
  <div v-click="1">
    <img border="rounded" src="/posture.jpg" width="360">
  </div>
</div>


<style>
.slidev-layout {
  font-size: 24px;
}
.flex {
  display: flex;
  margin-left: 28px;
}
.left {
  width: 300px;
}
.slidev-layout h1 {
  margin-bottom: 40px;
}
.slidev-layout h1 + p {
  margin-top: -0.5rem;
  margin-bottom: 2rem;
  opacity: 1;
}
.slidev-layout ul {
  padding-top: 20px;
}
.slidev-layout li {
  padding-top: 12px;
}
</style>

---

# 体の不調の原因①

<div class="flex">
  <div class="left">

  <v-clicks>

  - 前屈みになって、顔が突き出た姿勢になっていた

  ↓<br>
  頭の重量は4~6kgあり、頭が前に出る姿勢だとその重量を支える負担がより大きくなる

  ↓<br>
  僧帽筋、肩甲挙筋、菱形筋といった肩甲骨周りの筋肉が硬くなる

  </v-clicks>

  </div>
  <div v-click="3">
    <img border="rounded" src="/muscle.jpg" width="480">
  </div>
</div>

<style>
  .left {
    width: 480px;
    margin-right: 40px;
  }
  ul {
    margin-top: 40px;
  }
</style>

---

# 体の不調の原因②

<div class="flex">
  <div class="left">
  
  <v-clicks>

  - 前屈みになっており、呼吸が浅くなっていた

  ↓<br>
  猫背や前かがみの姿勢は肺を圧迫し、息を深く吐いたり吸ったりできなくなる

  ↓<br>
  軽い酸欠状態になる

  </v-clicks>

  </div>
  <div v-click="1">
    <img border="rounded" src="/posture.jpg" width="480">
  </div>
</div>

<style>
  .left {
    width: 480px;
    margin-right: 40px;
  }
  ul {
    margin-top: 40px;
  }
</style>

---
class: px-20
---

# 改善方法

<div class="flex">
  <div class="left">

  - 椅子に深く腰掛ける
  - 足裏全体を床につける、足が床につかない場合は足台を利用する
  - 目からディスプレイまでの距離は40㎝以上確保する
  - ディスプレイの上端は、目の高さより低くする
  - 肘の屈曲角度は90°以上にする
  - 手首や前腕を載せられる机のスペースやひじ掛けを確保する
  - 背筋を伸ばすストレッチ、腰をひねるストレッチ

  </div>
  <div>
    <img border="rounded" src="/right-posture.jpg" width="480">
  </div>
</div>

<style>
  .left {
    width: 480px;
    margin-right: 40px;
  }
  ul {
    margin-top: 20px;
  }
  li {
    margin-top: 8px;
  }
</style>

---

# 実践していること

<div class="flex">
  <div class="left">

  - 足台の使用
  - クッションの利用
  - 外部キーボードの利用
  - ノートパソコン用の台を使用
  - ディスプレイの上端を目線のやや上に固定

  </div>
  <div class="right">
    <img border="rounded" src="/my-posture.jpg" width="200">
    <img border="rounded" src="/desk2.jpg" width="200">
  </div>
</div>

<style>
  .left {
    width: 480px;
    margin-right: 40px;
  }
  ul {
    margin-top: 40px;
  }
  li {
    margin-top: 16px;
  }
  img {
    margin-bottom: 20px;
  }
</style>

---

# 使用しているもの

<div class="img-wrapper">
  <img border="rounded" src="/book-stand.jpg" width="200" height="auto">
  <img border="rounded" src="/cushion.jpg" width="200" height="auto">
  <img border="rounded" src="/foot-rest.jpg" width="200" height="auto">
  <img border="rounded" src="/hhkb.jpeg" width="200" height="auto">
</div>

<div>

  - https://amzn.asia/d/c4ZkaA9
  - https://amzn.asia/d/98DsFjq
  - https://amzn.asia/d/5c0Q2mb
  - https://www.amazon.co.jp/HHKB-Professional-HYBRID-Type-S-%E8%8B%B1%E8%AA%9E%E9%85%8D%E5%88%97%EF%BC%8F%E7%99%BD/dp/B082TQK2SB?ref_=ast_sto_dp&th=1&psc=1

</div>

<style>
  .img-wrapper {
    display: flex;
  }
</style>

---

# 参考

- https://www.mediaid-online.jp/clinic_notes/information/403
- https://jin-chiryouin.com/blog2/874/
- https://style.nikkei.com/article/DGXKZO42760450S9A320C1W10600/
- https://www.office-com.jp/gimon/office-tips/office_sitting.html#content2-1


---

ご静聴ありがとうございました！

<style>
  p {
   display: flex;
   justify-content: center;
   align-items: center;
   height: 100%;
   font-size: 32px;
  }
</style>
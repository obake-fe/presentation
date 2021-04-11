# Todoリスト補講

2021/04/xx 朝長大地

---

## 今日も一日お疲れさまでした

---

<!-- .element: data-background-image="../../dist/asset/white.png" -->

## 今日の目標<!-- .element: class="text-black" -->

### 1. 講義の内容をなんとなく理解する<!-- .element: class="text-black" -->
### 2. todoリストをちょっと作ってみる<!-- .element: class="text-black" -->

---

## さっそく本題へ

---

## プログラムというのは、<br>同じ処理でもいろいろな書き方ができる

---

## 好き勝手に作ったら、<br>ぐちゃぐちゃになっちゃう

---

## 書き方のルールが必要

[comment]: <> (好き勝手に作ったらぐちゃぐちゃになる→だから思想が大事→今回はアプリケーションを作る→その上で大事なのはViewとLogicの分離→MVCとか具体の話)

---

## SPAアプリケーションを<br>作るときに大事なこと

---

<!-- .element: data-background-image="../../dist/asset/white.png" -->

## 見た目(View)とロジックを<br>分離すること<!-- .element: class="text-black" -->

---

## Viewとロジックの分離

<img class="" src="asset/view_logic.png" width="960px" height="auto" >
<br>↑つじけんさんのスライドから引用

---

## いろんな設計思想

- MVC (Model-View-Controller) 
- MVVM (Model-View-ViewModel)
- Flux などなど...

---

## 今日はFluxを使います

---

## Flux

<img class="" src="asset/flux.png" width="800px" height="auto" >

---

###  ストーリーでイメージしてみよう

---

## ハム太郎で理解するFlux

<img class="" src="asset/hamutaro.png" width="320px" height="auto" >

---

## Flux

<img class="" src="asset/flux_hamu.png" width="840px" height="auto" >

---

## 今日使うのはFlux + Reducer

---

## Flux + Reducer

<img class="" src="asset/flux_reducer_hamu.png" width="760px" height="auto" >

---

## イメージできましたか？
<img class="" src="asset/hamutaro.png" width="320px" height="auto" >

---

## 実際のコードを見ながら<br>確認していきましょう！

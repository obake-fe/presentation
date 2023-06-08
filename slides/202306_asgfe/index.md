# SP版サロンボード<br>プロジェクトに参画して<br>1ヶ月が経ちました<!-- .element: style="font-size: 2em" -->


2023/06/09&nbsp;&nbsp;&nbsp;&nbsp;朝長 大地

---

<!-- .element: data-background-image="../../dist/asset/white.png" class="filter" -->

## 今日話すこと<!-- .element: class="text-black" -->

- ①自己紹介<!-- .element: class="text-black none-dot" style="font-size: 0.98em" -->
- ②SPSBにジョインして苦労していること<!-- .element: class="text-black none-dot" style="font-size: 0.98em" -->
- ③SPSBにジョインする前にやってて良かったこと<!-- .element: class="text-black none-dot" style="font-size: 0.98em" -->
- ④参画して1ヶ月で感じること<!-- .element: class="text-black none-dot" style="font-size: 0.98em" -->

---

## 自己紹介

- 朝長 大地（ともなが だいち）
- 長崎県大村市出身
- Nijibox入社6年目
- 2023年5月からSP版SBチームにジョイン

---

## 過去の案件
- 社内でいろいろ（1年半）
  - HTML、SCSS、jQuery、Gulp
- リクナビイベント（1年半）
  - HTML、JSP、CSS、jQuery
- knowbe（2年半）
  - React、TypeScript、Redux、MUI

---

## SPSB参画前のスキルセット
- Next.js
  - 公式チュートリアルをやりました
- GraphQL
  - @Quramyさんの研修をやりました
- Relay、Yoga、Zod、MSW ...etc
  - 経験なし

---

<!-- .element: data-background-image="../../dist/asset/white.png" class="filter" -->

[//]: # (## 今日話すこと<!-- .element: class="text-black" -->)

- ①自己紹介<!-- .element: class="text-black none-dot" style="font-size: 0.98em" -->
- ②SPSBにジョインして苦労していること<!-- .element: class="text-blue none-dot fw" style="font-size: 0.98em" -->
- ③SPSBにジョインする前にやってて良かったこと<!-- .element: class="text-black none-dot" style="font-size: 0.98em" -->
- ④参画して1ヶ月で感じること<!-- .element: class="text-black none-dot" style="font-size: 0.98em" -->

---

## Next.jsがわからない
- Reactと同じではない
- レンダリング場所という概念
  - SSRとCSRのどちらなのかを考える必要がある
- SPSBではgIPを使っているので特にそう
  - Relayのキャッシュを有効利用するため

---

## Relayキャッシュがわからない
- ReduxのStoreみたいなもの？
- Environmentという概念
- 利用する仕組みはすでに実装されている
  - 普通の実装では触らない部分

---

## エラー監視・解析がわからない
- Sentry、DataDog、Redash、Google Analytics
- 実践でしか経験値をつみにくい
- 仕様の理解やドメイン知識がないと難しい

[//]: # (- SSR/CSRどっちのエラー？)

---

## ライブラリの仕組みがわからない<!-- .element: style="font-size: 1.5em" -->
- MSW
  - Service Worker？
- dataloader
  - 遅延読み込みでn+1問題の解消？
- Zodios
  - helper関数？

---

## 新しめのCSSがわからない
どんどんアップデートされていた

```css
/* 論理的プロパティ */
.hoge {
  margin-inline: auto;   /* 左右センタリング */
}

/* gapを使ったmargin調整 */
.fuga {
  display: flex;
  gap: 30px 20px;
}
```

---

<!-- .element: data-background-image="../../dist/asset/white.png" class="filter" -->

[//]: # (## 今日話すこと<!-- .element: class="text-black" -->)

- ①自己紹介<!-- .element: class="text-black none-dot" style="font-size: 0.98em" -->
- ②SPSBにジョインして苦労していること<!-- .element: class="text-black none-dot" style="font-size: 0.98em" -->
- ③SPSBにジョインする前にやってて良かったこと<!-- .element: class="text-blue none-dot fw" style="font-size: 0.98em" -->
- ④参画して1ヶ月で感じること<!-- .element: class="text-black none-dot" style="font-size: 0.98em" -->

---

## GraphQLの事前予習
- OREILLYの『初めてのGraphQL』を読んで画像投稿アプリを作ってみた
- 本ではApolloを使っていたが、Relay/Yogaにも十分応用できる内容だった
- 実践に近いところまで見ていた
  - フラグメントコロケーション

---

## アジャイルの事前予習
- SPSBではアジャイルに近いフローを採用している<!-- .element: style="font-size: 0.98em" -->
- 書籍を読んでいたことが役立った
  - 『アジャイルサムライ』
  - 『エンジニア組織論への招待』<!-- .element: style="font-size: 0.98em" -->

---

<!-- .element: data-background-image="../../dist/asset/white.png" class="filter" -->

[//]: # (## 今日話すこと<!-- .element: class="text-black" -->)

- ①自己紹介<!-- .element: class="text-black none-dot" style="font-size: 0.98em" -->
- ②SPSBにジョインして苦労していること<!-- .element: class="text-black none-dot" style="font-size: 0.98em" -->
- ③SPSBにジョインする前にやってて良かったこと<!-- .element: class="text-black none-dot" style="font-size: 0.98em" -->
- ④参画して1ヶ月で感じること<!-- .element: class="text-blue none-dot fw" style="font-size: 0.98em" -->

---

## 途中参画の難しさ
- 途中参画だと既存のルールや仕様がある
  - そこの理解がないと色んなことが難しい
  - PRレビュー、エラー監視、MTG
- 「予定」「予約」などのドメイン概念

---

## フォローのありがたさ

- なんでも質問できる環境
  - ハドル、スレッド、モブプロ
- コンフルの資料も充実
- コードにもコメントが書かれているので、理解の助けになる

---

## これから

- サービスの仕様とその背景をまず理解する
  - 主要なページの作り、機能を読み解いていく

- 技術的な理解を進める
  - Rの新卒研修をやりました（Next.js）
  - 同様のアーキテクチャで何か作ってみる予定

---

## 最後に

- 今後成長した発表をできたらと思います！
- 技術的な話はこの後に先輩たちがやってくれます！

---

<!-- .element: data-background-image="../../dist/asset/white.png" class="filter" -->

## 引き続き頑張ります！<!-- .element: class="text-black" -->

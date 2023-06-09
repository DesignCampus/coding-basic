---
theme: "simple"
customTheme : "dc-theme"
transition: "convex"
slideNumber: false
title: "コーディング基礎 - JavaScript"
---

# コーディング基礎<br>ライブ授業
<h2 class="firstPage">2週目「JavaScript」</h2>
<img src="./img/logo_bg_none.png" style="width: 16%;">

---

1. 先週の課題
1. JavaScript？jQuery？
1. JavaScriptの復習
1. consoleを使う
1. JavaScriptとjQueryで似てるけど違う書き方
1. 実習：TOPに戻るボタン
1. 実習：classの付け替え
1. 次回に向けて

---

## 先週の課題

---

## JavaScript？jQuery？

--

ライブ授業ではjQueryは使いません

--

素のJavaScript = Vanilla.js（バニラJS）

--

なんでか

--

昔はjQueryを使わないと面倒だったことが  
今はバニラで簡単にできるから

--

例えば要素を取得する命令

querySelector()

--

```
document.querySelector('.demo')
```
.demoの要素を取得する

--

2008からJSで使えるように

--

jQueryは2006にリリース

--

```
$('.demo')
```

--

で簡単に取得できた

--

### ライブラリとフレームワーク

--

- ライブラリ：  
便利な機能を詰め合わせた部品の集まり(jQuery)
- フレームワーク：  
すでに骨組みが作られていてそれに沿って開発する(react.js、vue.js)

--

### TypeScript

--

代替JSやスーパーセットと言われるJavaScriptの拡張言語

---

## JavaScriptの復習

--

### JavaScriptでできること

--

- Webサイトに動きをつけて表現の幅を広げる
- モーダルやデータの処理や計算などで便利な仕組みをつくる

--

### CSSとJSの使い分け

--

- コーディングの基礎の段階ではCSSでできることはCSSでやると決めてしまおう
- 判断基準は状態の変化とユーザーのアクションにするのが良い
- 基本はJSでclassの付け替え等で状態を変化させて、変化後の動作はCSSみたいなイメージで

<small>※JSでやるほうが便利だったり早かったり、見通しが良かったりということもあるけれど今は気にしないでいい</small>

--

### 初級の内容

--

- JSの処理の流れ
- 変数
- 条件分岐
- 繰り返し
- 配列

基本はANYのリファレンス等でも学べます

---

## consoleを使う

--

example/js-console.html

---

## JavaScriptとjQueryで似てるけど違う書き方

---

## 実習：TOPに戻るボタン

--

### 条件＆ヒント

- HTMLは共通
- HTML内のbutton要素をクリックしたらページの最上部に戻る
- JSだけでなくCSSも少しは書く必要がある
- スクロールの動作を確認するため、CSSでダミー要素に高さを持たせる。
- スクロールにはwindow.scrollもしくはwindow.scrollToを使えば実現できる。またbehaviorプロパティを使ってスムーズなスクロールを実現する
- JSはhead内に記述。head内に記述するということは・・・

---

## 実習：classの付け替え

--

### 条件＆ヒント

- HTMLは共通
- HTML内のbutton要素をクリックしたら#js-demoの要素に.demo-onが付いたり消えたりする
- 絶対必要ではないが、JSだけでなくCSSも少しは書いたほうが見やすい
- scriptはbodyタグを閉じる直前にあるので、Topに戻るボタンの時より気にすることが少ない
- classの付け替えには、classList.○○を使えば簡単

---

<span style="font-size: 1.6em;">11:45 まで</span>

---

## 来週に向けて

--

### 課題

--

#### 実習の2つを完成させる  
<small>提出はファイル一式をzipに圧縮して提出してください</small>

<small>期限は6月15日 23：59</small>

<small>🔥 Firefox八王子のサイトも進めてね 🦊</small>


--



### 予告

サーバーUPだよ





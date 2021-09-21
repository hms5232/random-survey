# random-survey
會隨機派發問卷（或你想要的網址們）的入口

## 介紹
有些時候，我們會有需要隨機派發不同版本問卷的需求，或是要讓使用者隨機前往其中一個網址。這時候就可以讓這個小專案來幫忙。

## 使用方式
在 [`url.js`](url.js) 中填入自己想要隨機派發的問卷網址們（注意頁面上提示的規則），其他檔案不須更動。

之後將 `index.html` 作為入口發布，當使用者進入時就會由程式隨機抽出其中一個網址並將使用者重新導向過去。

### 範例
![GitHub deployments](https://img.shields.io/github/deployments/hms5232/random-survey/github-pages)

本儲存庫的 Github Pages 將會依照 `url.js` 隨機將使用者導向本人的 Github 或 Gitlab 等地方。👇  
https://hms5232.github.io/random-survey/

## 鳴謝
本專案係參考[〈【html javascript】隨機分配問卷〉](http://g23988.blogspot.com/2015/08/html-javascript.html)之概念改寫而成。感謝前人大大的無私分享。

## LICNESE
See [LICENSE file](LICENSE).

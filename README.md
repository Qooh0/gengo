# 元号変換プログラム

## 目的

お金欲しい！  
[この記事](http://www.yomiuri.co.jp/politics/20180520-OYT1T50149.html) によると、日付データの変換に10億円ほどかかるそうだ。  
1/100 でいいからほしい。ダメだったら 1/144 でもいい(謎)

## このプログラムは？

明治以降の和暦←→西暦変換を作りました。  
文字コードは UTF-8 にしか対応していませんが、変換プログラムです。

## この変換プログラムのすごい所

このプログラムでは、昭和64年などに対応しています。

## 使い方

### 西暦 → 和暦

seireki に日付を渡して、下記の URL にアクセスすれば和暦がわかります   
例) 2017年1月10日を検索

`https://qooh0.github.io/gengo/index.html?seireki=20170110`

### 和暦 → 西暦

wareki に日付を渡して、下記の URL にアクセスすれば和暦がわかります   
例) 昭和23年を検索

`https://qooh0.github.io/gengo/index.html?wareki=昭和23`

## ツッコミどころ

時間を思ったより使ってしまったので、いろいろ足りていません。  

## 独り言

簡単に JSON 返せなかったので、ちょっとハマった。  
https://firegoby.jp/archives/6631 とか使うと幸せになれるのかな？

## Donate.

もしよかったら、いくらか寄付していただけるとうれしいです。  
[寄付する！](https://paypal.me/qooh0/)

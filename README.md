# 《切韻》音系自動推導實例

## 使用方法

```
https://cdn.jsdelivr.net/gh/nk2028/qieyun-examples@<commit-sha>/<filename>
```

## 收錄實例列表

中文名稱 | 英文名稱 | 檔案名
:- | :- | :-
古韻羅馬字 | Koxyonh Romanization | `kyonh.js`
白一平轉寫 | Baxter’s Transcription | `baxter.js`
unt 切韻朗讀音 | unt’s Reading Pronunciation of _Qieyun_ | `unt.js`
unt 切韻擬音 J | unt's _Qieyun_ Reconstruction J | `unt_j.js`
推導普通話 | Extrapolated Putonghua | `putonghua.js`
推導廣州音 | Extrapolated Cantonese | `gwongzau.js`
綾香思考音系 | | `ayaka_v8.js`

## 備註

本項目遵從 [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)（非強制）。

首先安裝 Linter：

```sh
npm install
```

提交前請使用如下命令檢查，並儘可能修復錯誤：

```sh
./lint.sh <filename>
```

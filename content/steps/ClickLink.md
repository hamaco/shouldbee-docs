---
date: 2014-12-08T16:01:27+09:00
description: null
slug: null
tags: []
title: 「リンク名」のリンク先へ移動する
---

任意のリンクをクリックするステップ。


## 変数

変数名 | 説明
------|---------
`リンク名` | `<a>`タグのテキスト、id属性・title属性などが利用可能。


## 「新規登録」のリンクをクリックする例

```
「新規登録」のリンク先へ移動する
```

## 探索対象の要素

このステップは下記の順番でマッチする要素を探していきます。

```
<a href="..." id="リンク名">...</a>
<a href="..." title="リンク名">...</a>
<a href="..." rel="リンク名">...</a>
<a href="...">リンク名</a>
<a href="..."><img alt="リンク名"/></a>

<* role="link" id="login">リンク名</*>
<* role="link" value="login">リンク名</*>
<* role="link" title="login">リンク名</*>
<* role="link">リンク名</*>
```

上記の`*`はタグ名を限定しないという意味です。

## 別の表記

* 「`リンク名`」のリンクをクリックする

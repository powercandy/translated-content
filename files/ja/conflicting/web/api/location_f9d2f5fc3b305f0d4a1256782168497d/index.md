---
title: location.username
slug: conflicting/Web/API/Location_f9d2f5fc3b305f0d4a1256782168497d
tags:
  - API
  - Location
  - プロパティ
  - リファレンス
translation_of: Web/API/Location/username
original_slug: Web/API/Location/username
browser-compat: api.Location.username
---

{{deprecated_header}}

**`username`** は {{domxref("Location")}} インターフェイスのプロパティで、ドメイン名の前に指定されたユーザー名を表す {{domxref("USVString")}} です。

## 構文

```js
string = object.username;
object.username = string;
```

## 例

```js
// Let's <a id="myAnchor" href="https://anonymous:flabada@developer.mozilla.org/ja/docs/Location.username"> be in the document
var anchor = document.getElementByID("myAnchor");
var result = anchor.username; // Returns:'anonymous'
```

## ブラウザーの互換性

{{Compat}}

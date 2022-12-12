---
title: Element.createShadowRoot()
slug: conflicting/Web/API/Element/shadowRoot
tags:
  - API
  - Deprecated
  - Element
  - メソッド
  - 標準外
  - リファレンス
  - シャドウ DOM
translation_of: Web/API/Element/createShadowRoot
original_slug: Web/API/Element/createShadowRoot
browser-compat: api.Element.createShadowRoot
---

{{APIRef('Shadow DOM')}}{{non-standard_header}}{{deprecated_header}}

`Element.createShadowRoot` は[シャドウ DOM](/ja/docs/Web/Web_Components/Using_shadow_DOM) のインスタンスを作成するために使用し案す。シャドウ DOM が作成されると、常に既存の要素に割り当てられます。シャドウ DOM が作成された後、それが割り当てられている要素を{{glossary("shadow root", "シャドウルート")}}と呼びます。

> **Note:** このメソッドは非推奨となり、 {{DOMxRef("Element.attachShadow()","attachShadow()")}} に置き換えられました。

## 構文

```js
var shadowroot = element.createShadowRoot();
```

### 引数

引数はありません。

### 返値

{{DOMxRef("ShadowRoot")}} を返します。

## 仕様書

この機能は仕様書で定義されなくなりました。

## ブラウザーの互換性

{{Compat}}

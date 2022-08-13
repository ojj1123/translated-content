---
title: 'Window: beforeprint イベント'
slug: Web/API/Window/beforeprint_event
tags:
  - Event
  - Reference
translation_of: Web/API/Window/beforeprint_event
---
{{APIRef}}

**`beforeprint`** イベントは、関連する文書が印刷される直前や、印刷プレビューが開く直前に発生します。

| バブリング                   | いいえ                                                                                   |
| ---------------------------- | ---------------------------------------------------------------------------------------- |
| キャンセル                   | 不可                                                                                     |
| インターフェイス             | {{domxref("Event")}}                                                             |
| イベントハンドラープロパティ | {{domxref("WindowEventHandlers/onbeforeprint", "onbeforeprint")}} |

## 例

`addEventListener()` の使用例:

```js
window.addEventListener('beforeprint', (event) => {
  console.log('Before print');
});
```

`onbeforeprint` イベントハンドラープロパティの使用例:

```js
window.onbeforeprint = (event) => {
  console.log('Before print');
};
```

## 仕様書

| 仕様書                                                           | 状態                             |
| ---------------------------------------------------------------- | -------------------------------- |
| {{SpecName('HTML WHATWG', '#event-beforeprint')}} | {{Spec2('HTML WHATWG')}} |

## ブラウザーの互換性

{{Compat("api.Window.beforeprint_event")}}

## 関連情報

- 関連イベント: {{domxref("Window/afterprint_event", "afterprint")}}
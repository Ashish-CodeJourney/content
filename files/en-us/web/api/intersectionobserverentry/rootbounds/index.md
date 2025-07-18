---
title: "IntersectionObserverEntry: rootBounds property"
short-title: rootBounds
slug: Web/API/IntersectionObserverEntry/rootBounds
page-type: web-api-instance-property
browser-compat: api.IntersectionObserverEntry.rootBounds
---

{{APIRef("Intersection Observer API")}}

The **`rootBounds`** read-only property of the {{domxref("IntersectionObserverEntry")}} interface is a {{domxref("DOMRectReadOnly")}} corresponding to the {{domxref("IntersectionObserverEntry.target", "target")}}'s root intersection rectangle, offset by the {{domxref("IntersectionObserver.rootMargin")}} if one is specified.

## Value

A {{domxref("DOMRectReadOnly")}} which describes the root intersection rectangle.
For roots which are the {{domxref("Document")}}'s viewport, this rectangle is the bounds rectangle of the entire document.
Otherwise, it's the bounds of the root element.

This rectangle is offset by the values in {{domxref("IntersectionObserver.rootMargin")}}.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

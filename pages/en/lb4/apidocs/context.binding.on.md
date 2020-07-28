---
lang: en
title: 'API docs: context.binding.on'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/context
permalink: /doc/en/lb4/apidocs.context.binding.on.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/context](./context.md) &gt; [Binding](./context.binding.md) &gt; [on](./context.binding.on.md)

## Binding.on() method

The "changed" event is emitted by methods such as `tag`<!-- -->, `inScope`<!-- -->, `to`<!-- -->, and `toClass`<!-- -->.

<b>Signature:</b>

```typescript
on(eventName: 'changed', listener: BindingEventListener): this;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  eventName | 'changed' | The name of the event - always <code>changed</code>. |
|  listener | [BindingEventListener](./context.bindingeventlistener.md) | The listener function to call when the event is emitted. |

<b>Returns:</b>

this


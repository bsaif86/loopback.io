---
lang: en
title: 'API docs: filter.keyof'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/filter
permalink: /doc/en/lb4/apidocs.filter.keyof.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/filter](./filter.md) &gt; [KeyOf](./filter.keyof.md)

## KeyOf type

Key types of a given model, excluding operators

<b>Signature:</b>

```typescript
export declare type KeyOf<MT extends object> = Exclude<Extract<keyof MT, string>, Operators>;
```

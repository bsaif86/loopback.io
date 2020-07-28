---
lang: en
title: 'API docs: express.registerexpressmiddlewareinterceptor'
keywords: LoopBack 4.0, LoopBack 4, Node.js, TypeScript, OpenAPI
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/express
permalink: /doc/en/lb4/apidocs.express.registerexpressmiddlewareinterceptor.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/express](./express.md) &gt; [registerExpressMiddlewareInterceptor](./express.registerexpressmiddlewareinterceptor.md)

## registerExpressMiddlewareInterceptor() function

Bind a middleware interceptor to the given context

<b>Signature:</b>

```typescript
export declare function registerExpressMiddlewareInterceptor<CFG>(ctx: Context, middlewareFactory: ExpressMiddlewareFactory<CFG>, middlewareConfig?: CFG, options?: MiddlewareInterceptorBindingOptions): Binding<GenericInterceptor<InvocationContext>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  ctx | [Context](./context.context.md) | Context object |
|  middlewareFactory | [ExpressMiddlewareFactory](./express.expressmiddlewarefactory.md)<!-- -->&lt;CFG&gt; | Express middleware factory function |
|  middlewareConfig | CFG | Express middleware config |
|  options | [MiddlewareInterceptorBindingOptions](./express.middlewareinterceptorbindingoptions.md) | Options for registration |

<b>Returns:</b>

[Binding](./context.binding.md)<!-- -->&lt;[GenericInterceptor](./context.genericinterceptor.md)<!-- -->&lt;[InvocationContext](./context.invocationcontext.md)<!-- -->&gt;&gt;


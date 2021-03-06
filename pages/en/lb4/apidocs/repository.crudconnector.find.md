---
lang: en
title: 'API docs: repository.crudconnector.find'
keywords: LoopBack 4.0, LoopBack 4
sidebar: lb4_sidebar
editurl: https://github.com/strongloop/loopback-next/tree/master/packages/repository
permalink: /doc/en/lb4/apidocs.repository.crudconnector.find.html
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@loopback/repository](./repository.md) &gt; [CrudConnector](./repository.crudconnector.md) &gt; [find](./repository.crudconnector.find.md)

## CrudConnector.find() method

Find matching entities by the filter

<b>Signature:</b>

```typescript
find(modelClass: Class<Entity>, filter?: Filter, options?: Options): Promise<EntityData[]>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  modelClass | <code>Class&lt;Entity&gt;</code> | The model class |
|  filter | <code>Filter</code> | The query filter |
|  options | <code>Options</code> | Options for the operation |

<b>Returns:</b>

`Promise<EntityData[]>`

A promise of an array of entities found for the filter



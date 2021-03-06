<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@firebase/firestore](./firestore.md) &gt; [/](./firestore_.md) &gt; [QueryDocumentSnapshot](./firestore_.querydocumentsnapshot.md)

## QueryDocumentSnapshot class

A `QueryDocumentSnapshot` contains data read from a document in your Firestore database as part of a query. The document is guaranteed to exist and its data can be extracted with `.data()` or `.get(<field>)` to get a specific field.

A `QueryDocumentSnapshot` offers the same API surface as a `DocumentSnapshot`<!-- -->. Since query results contain only existing documents, the `exists` property will always be true and `data()` will never return 'undefined'.

<b>Signature:</b>

```typescript
export declare class QueryDocumentSnapshot<T = DocumentData> extends DocumentSnapshot<T> 
```
<b>Extends:</b> [DocumentSnapshot](./firestore_.documentsnapshot.md)<!-- -->&lt;T&gt;

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [data(options)](./firestore_.querydocumentsnapshot.data.md) |  | Retrieves all fields in the document as an <code>Object</code>.<!-- -->By default, <code>FieldValue.serverTimestamp()</code> values that have not yet been set to their final value will be returned as <code>null</code>. You can override this by passing an options object. |


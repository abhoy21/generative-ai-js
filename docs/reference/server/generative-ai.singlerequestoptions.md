<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/generative-ai](./generative-ai.md) &gt; [SingleRequestOptions](./generative-ai.singlerequestoptions.md)

## SingleRequestOptions interface

Params passed to atomic asynchronous operations.

**Signature:**

```typescript
export interface SingleRequestOptions extends RequestOptions 
```
**Extends:** [RequestOptions](./generative-ai.requestoptions.md)

## Properties

<table><thead><tr><th>

Property


</th><th>

Modifiers


</th><th>

Type


</th><th>

Description


</th></tr></thead>
<tbody><tr><td>

[signal?](./generative-ai.singlerequestoptions.signal.md)


</td><td>


</td><td>

AbortSignal


</td><td>

_(Optional)_ An object that may be used to abort asynchronous requests. The request may also be aborted due to the expiration of the timeout value, if provided.

NOTE: AbortSignal is a client-only operation. Using it to cancel an operation will not cancel the request in the service. You will still be charged usage for any applicable operations.


</td></tr>
</tbody></table>

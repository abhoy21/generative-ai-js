<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/generative-ai](./generative-ai.md) &gt; [GenerateContentStreamResult](./generative-ai.generatecontentstreamresult.md)

## GenerateContentStreamResult interface

Result object returned from generateContentStream() call. Iterate over `stream` to get chunks as they come in and/or use the `response` promise to get the aggregated response when the stream is done.

**Signature:**

```typescript
export interface GenerateContentStreamResult 
```

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

[response](./generative-ai.generatecontentstreamresult.response.md)


</td><td>


</td><td>

Promise&lt;[EnhancedGenerateContentResponse](./generative-ai.enhancedgeneratecontentresponse.md)<!-- -->&gt;


</td><td>


</td></tr>
<tr><td>

[stream](./generative-ai.generatecontentstreamresult.stream.md)


</td><td>


</td><td>

AsyncGenerator&lt;[EnhancedGenerateContentResponse](./generative-ai.enhancedgeneratecontentresponse.md)<!-- -->&gt;


</td><td>


</td></tr>
</tbody></table>

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/generative-ai](./generative-ai.md) &gt; [GenerativeModel](./generative-ai.generativemodel.md) &gt; [embedContent](./generative-ai.generativemodel.embedcontent.md)

## GenerativeModel.embedContent() method

Embeds the provided content.

Fields set in the optional [SingleRequestOptions](./generative-ai.singlerequestoptions.md) parameter will take precedence over the [RequestOptions](./generative-ai.requestoptions.md) values provided to [GoogleGenerativeAI.getGenerativeModel()](./generative-ai.googlegenerativeai.getgenerativemodel.md)<!-- -->.

**Signature:**

```typescript
embedContent(request: EmbedContentRequest | string | Array<string | Part>, requestOptions?: SingleRequestOptions): Promise<EmbedContentResponse>;
```

## Parameters

<table><thead><tr><th>

Parameter


</th><th>

Type


</th><th>

Description


</th></tr></thead>
<tbody><tr><td>

request


</td><td>

[EmbedContentRequest](./generative-ai.embedcontentrequest.md) \| string \| Array&lt;string \| [Part](./generative-ai.part.md)<!-- -->&gt;


</td><td>


</td></tr>
<tr><td>

requestOptions


</td><td>

[SingleRequestOptions](./generative-ai.singlerequestoptions.md)


</td><td>

_(Optional)_


</td></tr>
</tbody></table>
**Returns:**

Promise&lt;[EmbedContentResponse](./generative-ai.embedcontentresponse.md)<!-- -->&gt;


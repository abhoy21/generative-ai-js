<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/generative-ai](./generative-ai.md) &gt; [GenerateContentResponse](./generative-ai.generatecontentresponse.md)

## GenerateContentResponse interface

Individual response from [GenerativeModel.generateContent()](./generative-ai.generativemodel.generatecontent.md) and [GenerativeModel.generateContentStream()](./generative-ai.generativemodel.generatecontentstream.md)<!-- -->. `generateContentStream()` will return one in each chunk until the stream is done.

**Signature:**

```typescript
export interface GenerateContentResponse 
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

[candidates?](./generative-ai.generatecontentresponse.candidates.md)


</td><td>


</td><td>

[GenerateContentCandidate](./generative-ai.generatecontentcandidate.md)<!-- -->\[\]


</td><td>

_(Optional)_ Candidate responses from the model.


</td></tr>
<tr><td>

[promptFeedback?](./generative-ai.generatecontentresponse.promptfeedback.md)


</td><td>


</td><td>

[PromptFeedback](./generative-ai.promptfeedback.md)


</td><td>

_(Optional)_ The prompt's feedback related to the content filters.


</td></tr>
<tr><td>

[usageMetadata?](./generative-ai.generatecontentresponse.usagemetadata.md)


</td><td>


</td><td>

[UsageMetadata](./generative-ai.usagemetadata.md)


</td><td>

_(Optional)_ Metadata on the generation request's token usage.


</td></tr>
</tbody></table>

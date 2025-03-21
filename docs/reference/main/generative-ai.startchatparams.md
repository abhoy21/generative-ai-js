<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/generative-ai](./generative-ai.md) &gt; [StartChatParams](./generative-ai.startchatparams.md)

## StartChatParams interface

Params for [GenerativeModel.startChat()](./generative-ai.generativemodel.startchat.md)<!-- -->.

**Signature:**

```typescript
export interface StartChatParams extends BaseParams 
```
**Extends:** [BaseParams](./generative-ai.baseparams.md)

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

[cachedContent?](./generative-ai.startchatparams.cachedcontent.md)


</td><td>


</td><td>

string


</td><td>

_(Optional)_ This is the name of a `CachedContent` and not the cache object itself.


</td></tr>
<tr><td>

[history?](./generative-ai.startchatparams.history.md)


</td><td>


</td><td>

[Content](./generative-ai.content.md)<!-- -->\[\]


</td><td>

_(Optional)_


</td></tr>
<tr><td>

[systemInstruction?](./generative-ai.startchatparams.systeminstruction.md)


</td><td>


</td><td>

string \| [Part](./generative-ai.part.md) \| [Content](./generative-ai.content.md)


</td><td>

_(Optional)_


</td></tr>
<tr><td>

[toolConfig?](./generative-ai.startchatparams.toolconfig.md)


</td><td>


</td><td>

[ToolConfig](./generative-ai.toolconfig.md)


</td><td>

_(Optional)_


</td></tr>
<tr><td>

[tools?](./generative-ai.startchatparams.tools.md)


</td><td>


</td><td>

[Tool](./generative-ai.tool.md)<!-- -->\[\]


</td><td>

_(Optional)_


</td></tr>
</tbody></table>

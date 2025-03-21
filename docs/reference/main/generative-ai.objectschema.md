<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/generative-ai](./generative-ai.md) &gt; [ObjectSchema](./generative-ai.objectschema.md)

## ObjectSchema interface

Describes a JSON object, a mapping of specific keys to values.

**Signature:**

```typescript
export interface ObjectSchema extends BaseSchema 
```
**Extends:** BaseSchema

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

[properties](./generative-ai.objectschema.properties.md)


</td><td>


</td><td>

{ \[k: string\]: [Schema](./generative-ai.schema.md)<!-- -->; }


</td><td>

Describes the properties of the JSON object. Must not be empty.


</td></tr>
<tr><td>

[required?](./generative-ai.objectschema.required.md)


</td><td>


</td><td>

string\[\]


</td><td>

_(Optional)_ A list of keys declared in the properties object. Required properties will always be present in the generated object.


</td></tr>
<tr><td>

[type](./generative-ai.objectschema.type.md)


</td><td>


</td><td>

typeof [SchemaType.OBJECT](./generative-ai.schematype.md)


</td><td>


</td></tr>
</tbody></table>

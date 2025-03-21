<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/generative-ai](./generative-ai.md) &gt; [Outcome](./generative-ai.outcome.md)

## Outcome enum

Possible outcomes of code execution.

**Signature:**

```typescript
export declare enum Outcome 
```

## Enumeration Members

<table><thead><tr><th>

Member


</th><th>

Value


</th><th>

Description


</th></tr></thead>
<tbody><tr><td>

OUTCOME\_DEADLINE\_EXCEEDED


</td><td>

`"outcome_deadline_exceeded"`


</td><td>

Code execution ran for too long, and was cancelled. There may or may not be a partial output present.


</td></tr>
<tr><td>

OUTCOME\_FAILED


</td><td>

`"outcome_failed"`


</td><td>

Code execution finished but with a failure. `stderr` should contain the reason.


</td></tr>
<tr><td>

OUTCOME\_OK


</td><td>

`"outcome_ok"`


</td><td>

Code execution completed successfully.


</td></tr>
<tr><td>

OUTCOME\_UNSPECIFIED


</td><td>

`"outcome_unspecified"`


</td><td>

Unspecified status. This value should not be used.


</td></tr>
</tbody></table>

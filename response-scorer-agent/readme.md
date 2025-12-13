# response-scorer-agent

Evaluates the responses for each pair of LLM and prompt.

```typescript
// output
type EvaluationResponse = {
  mention: boolean;
  sentimentScore: number;
  ranking: number | null;
};
```

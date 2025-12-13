# prompt-generator-agent

This agent genereates prompts which are then executed in the selected LLMs of the search specification.

```typescript
// output
type PromptGeneratorOutput = {
  text: string;
  promptType: "ORGANIC" | "COMPETITOR" | "BRAND_SPECIFIC";
};
```

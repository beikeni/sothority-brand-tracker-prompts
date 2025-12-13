# report-generation-agent

This agent builds actionable reports for things that one can do to improve the AI visibility of their website.

```typescript
// output
type ReportOutput = {
  description: string;
  tasks: {
    title: string;
    type: "TECHNICAL" | "OUTREACH" | "CONTENT" | "GENERAL";
    order: number;
    steps: {
      description: string;
      order: number;
    }[];
  }[];
};
```

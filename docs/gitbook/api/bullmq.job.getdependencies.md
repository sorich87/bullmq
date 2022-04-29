<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [Job](./bullmq.job.md) &gt; [getDependencies](./bullmq.job.getdependencies.md)

## Job.getDependencies() method

Get children job keys if this job is a parent and has children.

<b>Signature:</b>

```typescript
getDependencies(opts?: DependenciesOpts): Promise<{
        nextProcessedCursor?: number;
        processed?: Record<string, any>;
        nextUnprocessedCursor?: number;
        unprocessed?: string[];
    }>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  opts | [DependenciesOpts](./bullmq.dependenciesopts.md) |  |

<b>Returns:</b>

Promise&lt;{ nextProcessedCursor?: number; processed?: Record&lt;string, any&gt;; nextUnprocessedCursor?: number; unprocessed?: string\[\]; }&gt;

dependencies separated by processed and unprocessed.

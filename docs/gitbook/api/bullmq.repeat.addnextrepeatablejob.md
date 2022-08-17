<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [bullmq](./bullmq.md) &gt; [Repeat](./bullmq.repeat.md) &gt; [addNextRepeatableJob](./bullmq.repeat.addnextrepeatablejob.md)

## Repeat.addNextRepeatableJob() method

<b>Signature:</b>

```typescript
addNextRepeatableJob<T = any, R = any, N extends string = string>(name: N, data: T, opts: JobsOptions, skipCheckExists?: boolean): Promise<Job<T, R, N>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  name | N |  |
|  data | T |  |
|  opts | [JobsOptions](./bullmq.jobsoptions.md) |  |
|  skipCheckExists | boolean |  |

<b>Returns:</b>

Promise&lt;[Job](./bullmq.job.md)<!-- -->&lt;T, R, N&gt;&gt;

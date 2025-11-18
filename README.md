# Evals Framework
This repository contains comparisions of various evals framework like Weights and Biases, Evidently AI, LangFuse and such

I am comparing tools for evulating classical ML models plus cutting edge LLM models.

## Comparisions
<table>
  <tr>
    <th></th>
    <th>Evidently AI</th>
    <th>Weights & Biases</th>
    <th>Lang Fuse</th>
  </tr>
  <tr>
    <td>Pros</td>
    <td>
      • for evaluating data quality, drift, model performance <br><br>
      • For LLMs, they support “descriptors” — row-level checks of outputs, such as length, semantic similarity, or even LLM-judged quality<br><br>
      • They allow “LLM-as-judge” evaluations: you can prompt another LLM to assess the quality or correctness of responses<br><br>
      • all in all for ensuring quality of the model<br><br>
    </td>
    <td>
      • focused on experiment tracking, model versioning, dataset versioning, hyperparameter tuning, and general ML lifecycle management<br><br>
      • For LLMs (and more “agentic” systems), W&B has added observability via Weave. According to them, Weave logs LLM calls, input/output, traces (sub-operations, e.g. retrieval, inference), latency, token usage
    </td>
    <td>
      • open-source LLM engineering platform<br><br>
      • Built for full LLMOps: trace → evaluate → iterate → deploy
      • built for observability, prompt management, evaluation, and agent tracing<br><br>
      • It captures detailed traces: inputs, outputs, tool usage, retries, latencies, cost per call, etc<br><br>
    </td>
  </tr>
  <tr>
    <td>Cons</td>
    <td>
      • “Developer” tier is free but production use will likely require paid plans<br><br>
    </td>
    <td>
      • Might be more heavyweight or “overkill” for pure LLM monitoring if you don’t need full experiment tracking<br><br>
      • “Developer” tier is free but production use will likely require paid plans<br><br>
    </td>
    <td>
      • self-hosting requires setup and maintenance.<br><br>
      • For very simple LLM use-cases (e.g., one-shot API calls), Langfuse might feel “too much”.<br><br>
    </td>
  </tr>
</table>




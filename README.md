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
      • for evaluating data quality, drift, model performance <br>
      • For LLMs, they support “descriptors” — row-level checks of outputs, such as length, semantic similarity, or even LLM-judged quality<br>
      • They allow “LLM-as-judge” evaluations: you can prompt another LLM to assess the quality or correctness of responses<br>
      • all in all for ensuring quality of the model<br>
    </td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Cons</td>
    <td>
      • It’s less about tracing how an LLM-based system made a decision<br>
      • Might not provide very deep observability for LLMs/agentic system<br>
    </td>
    <td></td>
    <td></td>
  </tr>
</table>




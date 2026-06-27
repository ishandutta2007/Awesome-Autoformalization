# The Self-Correcting & Reinforcement Learned Era

## Detailed Information
Modern autoformalization integrates language models into closed feedback loops with Interactive Theorem Provers (ITPs) like Lean 4. The model drafts code, the compiler type-checks it and returns error stack traces, and the LLM recursively corrects its code until the verifier passes it. This is reinforced via learning algorithms optimized for logical correctness.

## Diagram
```mermaid
flowchart TD
    NL[NL Statement] --> LLM[LLM Generator]
    LLM --> Draft[Formal Draft]
    Draft --> ITP[ITP Compiler / Lean 4]
    ITP -->|Error Trace| LLM
    ITP -->|Success| Verify[Verified Formal Statement]
```

## Navigation
[← Back to Main README](../README.md)

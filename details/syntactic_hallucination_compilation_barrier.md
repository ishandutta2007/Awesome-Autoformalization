# The Syntactic Hallucination & Compilation Barrier

## Detailed Information
LLMs often output syntactically invalid code that looks correct but fails compilation due to type errors, wrong library references, or syntactic bugs. Mitigated by using Compiler-in-the-Loop decoding, where the parser checks intermediate states.

## Diagram
```mermaid
flowchart LR
    Tokens[Draft Tokens] --> Compiler[ITP Compiler Type Checker]
    Compiler -->|Syntax Error| Backtrack[Backtrack and Regenerate]
    Compiler -->|Success| Next[Continue Generating Proof]
```

## Navigation
[← Back to Main README](../README.md)

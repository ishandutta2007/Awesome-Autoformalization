# Synthetic Informal-to-Formal Back-Translation

## Detailed Information
Overcomes data scarcity by taking vast, verified databases of formal math or code and translating them into natural language explanations. This creates a parallel corpus to train models for the reverse task: autoformalization.

## Diagram
```mermaid
flowchart TD
    Formal[Formal Library e.g. Mathlib] --> LLM[LLM Explainer]
    LLM --> NL[Generated NL Explanation]
    NL & Formal --> Parallel[Parallel Dataset]
    Parallel --> Train[Train Autoformalizer]
```

## Navigation
[← Back to Main README](../README.md)

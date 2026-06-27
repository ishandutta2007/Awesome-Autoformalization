# Theorem Prover Autoformalization (Math Domain)

## Detailed Information
This variant translates informal natural language mathematics into specialized languages verified by Interactive Theorem Provers (ITPs). Systems target platforms like Lean, Isabelle, Coq, and Mizar, allowing AI to verify mathematical statements and discover new mathematical theories alongside human researchers.

## Diagram
```mermaid
flowchart LR
    MathNL[Informal Math Paper] --> Parser[Autoformalization Engine]
    Parser --> Lean[Lean 4 Statement]
    Parser --> Coq[Coq Specification]
    Lean --> Verifier[ITP Core Verification]
```

## Navigation
[← Back to Main README](../README.md)

# Executable Abstract Syntax Tree (AST) Mapping

## Detailed Information
A lightweight autoformalization approach mapping natural language to structured abstract syntax trees, JSON schemas, database queries (SQL), or executable formats. By mapping directly to ASTs, semantic parsing can decouple language nuances from compiler syntax constraints.

## Diagram
```mermaid
flowchart TD
    NL[Natural Language Query] --> Parser[Semantic Parser]
    Parser --> AST[Abstract Syntax Tree]
    AST --> Code[Executable SQL / Schema]
```

## Navigation
[← Back to Main README](../README.md)

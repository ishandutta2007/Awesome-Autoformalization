# The Infinite Search State Space Problem

## Detailed Information
The mathematical proof search tree is incredibly large, and autoformalizing a statement can lead to multiple alternative definitions. Using Monte Carlo Tree Search (MCTS) or Process-Supervised Reward Models (PRMs) helps steer search steps toward valid verification branches.

## Diagram
```mermaid
flowchart TD
    Root[Informal Proof Goal] --> MCTS[Monte Carlo Tree Search]
    MCTS -->|Select/Expand| Nodes[Token Branches]
    Nodes --> PRM[Process Reward Model Score]
    PRM -->|High Score| Keep[Explore Path]
    PRM -->|Low Score| Prune[Prune Path]
```

## Navigation
[← Back to Main README](../README.md)

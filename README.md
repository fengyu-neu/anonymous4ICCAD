# DSA-MP Layout Decomposition Benchmark

A diverse benchmark for evaluating DSA-aware multiple patterning (DSA-MP) layout decomposition methods across design styles and technology nodes.

## Benchmark

The benchmark includes test layouts from three categories:

| Category | Node | Design Style | Count |
|----------|------|--------------|-------|
| Synthetic | 7nm | Synthetic layouts using ASAP7 PDK | 12 |
| BOOM Core | 7nm | RISC-V BOOM processor via Chipyard with ASAP7 PDK | 12 |
| Industrial | 5nm | Industrial logic SoC designs | 11 |

This benchmark enables evaluation of cross-node and cross-design-style generalization for layout decomposition algorithms.

## Synthetic Layout Generation

We provide a script for generating synthetic training layouts at the 7nm node that comply with ASAP7 design rules.

### Usage

```bash
python layout_generator.py
```

The generated layouts can be used to train machine learning models for DSA-MP layout decomposition without relying on proprietary design data.


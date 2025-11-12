# Multimodal Agent

This repository follows a modular layout to support the development of a multimodal M4 pipeline. The top-level structure is outlined below:

```
multimodal-agent/
├─ agent_main.py                # M4 orchestration entry point
├─ modules/
│  ├─ m1_alignment/             # Alignment and fusion components
│  ├─ m2_generation/            # Feedback generation modules
│  └─ m3_perception_planning/   # BEV perception and planning
├─ configs/                     # Experiment configurations (YAML)
├─ data/                        # Data indices and download scripts
├─ notebooks/                   # Visualization and analysis notebooks
├─ scripts/                     # Training, evaluation, and export scripts
├─ docs/
│  ├─ whitepaper.pdf
│  └─ ablation_report.md
```

Each directory currently contains placeholders to be expanded with implementation-specific assets.

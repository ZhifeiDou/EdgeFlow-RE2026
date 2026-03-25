# Dataset and result: VLM-based Flowchart Processing with Edge-Map Augmentation

This repository contains the replication package for the paper:

> **VLM-based Flowchart Processing with Edge-Map Augmentation: An Industrial RE Study**
> Zhifei Dou, Shabnam Hassani, Ou Wei
> IEEE Requirements Engineering 2026 — Industry Innovation Track

## Contents

- `FlowVQA_Dataset/Images/` — 40 sampled FlowVQA flowchart images used for cross-dataset evaluation (RQ3)
- `FlowVQA_Dataset/Ground_truth/` — Ground-truth Mermaid code for each image
- `FlowVQA_Result_Qwen3/` — Per-run evaluation results for Qwen3-VL-32B-Instruct (5 runs, baseline + EdgeFlow) on sampled FlowVQA
- `FlowVQA_Result_Qwen3.5/` — Per-run evaluation results for Qwen3.5-35B-A3B (5 runs, baseline + EdgeFlow) on sampled FlowVQA

Each `.xlsx` file contains one experimental run. Rows with batch names prefixed `batch_baseline_run_` are the baseline condition; rows prefixed `batch_canny_run_` are the EdgeFlow condition.

IndusReqFlow results (RQ1, RQ2) are not included due to the proprietary nature of Huawei's internal requirements documents.

## Citation

```bibtex
@inproceedings{dou2026edgeflow,
  title={{VLM}-based Flowchart Processing with Edge-Map Augmentation: An Industrial {RE} Study},
  author={Dou, Zhifei and Hassani, Shabnam and Wei, Ou},
  booktitle={Proceedings of the IEEE International Requirements Engineering Conference (RE) -- Industry Innovation Track},
  year={2026}
}
```

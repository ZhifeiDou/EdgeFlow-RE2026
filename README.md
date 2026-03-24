# EdgeFlow: VLM-based Flowchart Processing with Edge-Map Augmentation
### An Industrial Requirements Engineering (RE) Study for RE 2026

[![Submission](https://img.shields.io/badge/RE2026-Industry--Innovation-blue)](https://conf.researchr.org/home/re-2026)

## 📌 Overview
In industrial Requirements Engineering (RE), flowcharts are vital for documenting requirements and system behaviors. However, automated verification of these diagrams remains a challenge for standard Vision Language Models (VLMs).

**EdgeFlow** is a research framework designed to enhance VLM understanding of industrial flowcharts through **Edge-Map Augmentation**. By providing structural cues alongside visual data, we significantly improve the model's ability to trace logical paths and validate system requirements.

---

## 🚀 Key Contributions
* **Edge-Map Augmentation:** A specialized preprocessing technique that overlays structural edge detection to help VLMs better parse nodes and directed edges.
* **FlowVQA Dataset:** A curated dataset for Visual Question Answering (VQA) focusing on industrial flowchart reasoning and decision logic.
* **Comparative Benchmarking:** Evaluation of state-of-the-art models (Qwen series) demonstrating the performance lift provided by edge-based augmentation.

---

## 📂 Repository Structure
* **`FlowVQA_Dataset/`**: Contains the source flowchart images and VQA ground-truth.
* **`FlowVQA_Result_Qwen3/`**: Results and metrics for the Qwen3 model evaluations.
* **`FlowVQA_Result_Qwen3.5/`**: Comparative results for the Qwen3.5 model iterations.
* **`README.md`**: Project documentation and submission details.

---

## 📊 Evaluation Summary
Our study focuses on the "Logic Path Identification" accuracy, comparing baseline VLM performance against our augmented approach.

| Model Strategy | Accuracy (Baseline) | Accuracy (Edge-Map Aug) |
| :--- | :--- | :--- |
| **Qwen3 (7B)** |x% | **x%** |
| **Qwen3.5 (7B)** | x% | **x%** |

---

## 🛠️ How to Use
1. **Dataset:** Explore `/FlowVQA_Dataset` for the image-query pairs used in the study.
2. **Inference:** The results in the `/FlowVQA_Result` folders include the specific prompts used to achieve the reported accuracy.
3. **Augmentation:** The edge maps can be generated using standard Canny edge detection before being passed to the VLM.

---

## 📝 Authors & Citation
This work is part of an industrial RE study submitted to the **IEEE Requirements Engineering 2026 Industry Innovation Track**.

**Authors:**
* **Zhifei Dou**
* **Shabnam Hassani**
* **Ou Wei**

If you find this repository useful for your research, please cite:

```bibtex
@inproceedings{dou2026edgeflow,
  title={VLM-based Flowchart Processing with Edge-Map Augmentation: An Industrial RE Study},
  author={Dou, Zhifei and Hassaniahari, Shabnam},
  booktitle={IEEE Requirements Engineering Conference (RE) - Industry Innovation Track},
  year={2026}

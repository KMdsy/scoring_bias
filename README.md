# Evaluating Scoring Bias in LLM-as-a-Judge

This is the official repository for the paper:
**Evaluating Scoring Bias in LLM-as-a-Judge**
[<link>](https://arxiv.org/abs/2506.22316)

This repository will contain the data resources introduced in the paper, designed to facilitate research on scoring bias in LLM-as-a-Judge evaluations.

## 🚀 Data Resources

To address the critical lack of datasets for scoring bias analysis, we introduce an automatic data synthesis pipeline that expands existing LLM-as-a-Judge benchmarks FLASK and BiGGen into a tailored evaluation corpus, thereby establishing a foundational resource for future studies.

This repository will host the augmented versions of two key benchmarks:
1.  **Augmented FLASK**
2.  **Augmented BiGGen**

The primary enhancement for both datasets is the inclusion of **four distinct reference answers for each data instance**, generated to correspond to specific quality scores (e.g., Scores 1, 2, 3, and 4), allowing for a controlled study of reference answer score bias.

### ⚠️ Important Notice: Data Availability

**The complete, augmented FLASK and BiGGen datasets are currently undergoing a mandatory data disclosure review by the authors' employer.**

We are committed to transparency and open science. The full datasets will be made publicly available in this repository immediately following the completion and approval of this review. We appreciate your patience and understanding.

---

## 💡 Data Synthesis Pipeline

The high-level flowchart of this pipeline (as shown in our paper) is as follows:

![Data Synthesis Pipeline Flowchart](./assets/pipeline_flowchart.png)

---

## 📋 Data Examples

Here is a conceptual, placeholder example of the data structure for each augmented dataset.

### Augmented FLASK Example
```json

```


### Augmented BiGGen Example
```json

```

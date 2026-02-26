# Text-to-SQL Generation using T5-Large with Schema-Aware Encoding

This project demonstrates how large language models can translate natural language questions into SQL queries with high accuracy by leveraging schema-aware input formatting and transformer-based architectures.

---

## Overview

Querying databases using SQL can be challenging for non-technical users.  
Our project bridges this gap by fine-tuning **T5-Large** to generate SQL queries directly from natural language inputs.

By providing the model with both the question and the corresponding database schema, we significantly improve its ability to generalize across complex and unseen databases.

---

## Key Features

- Schema-aware encoding for improved SQL understanding  
- Fine-tuned **T5-Large** model using Hugging Face  
- Achieved **70% Exact Match Accuracy** on the Spider dataset  
- End-to-end pipeline for training, validation, and inference  
- Built using:
  - Hugging Face Transformers  
  - Datasets  
  - Accelerate  

---

## Model Performance

| Metric | Score |
|--------|--------|
| **Exact Match Accuracy** | **70%** |

Schema-aware formatting helps the model generate accurate SQL structures even for unseen database schemas.

---


---

## Approach Summary

- Natural language questions are combined with structured schema descriptions  
- T5-Large is fine-tuned on the Spider benchmark  
- Schema context improves table/column alignment  
- Model generalizes well to unseen databases  

---

## Dataset

This project uses the **Spider** dataset, a large-scale and cross-domain text-to-SQL benchmark.  
More details: https://yale-lily.github.io/spider

---

## Acknowledgements

- Hugging Face Transformers, Datasets, and Accelerate  
- Spider dataset creators  
- Google T5 authors  

---

Feel free to explore the notebook for full training, evaluation, and experiments!



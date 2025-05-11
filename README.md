# CONTRAST: Contrastive Temperature-Regulated Adaptive Session Training

This is the official implementation for the *"Adaptive Session-based Recommendation with Contrastive Learning"* paper. It includes data processing of datasets (RetailRocket and Diginetica) that we used to train and test our model. 

### 🔗 Notebooks on Kaggle
- **[CONTRAST Data Pipeline](https://www.kaggle.com/code/farneetsingh24/contrast-data-pipeline)**: Clean, transform, and structure raw data into usable session datasets.
- **[CONTRAST Model Implementation](https://www.kaggle.com/code/farneetsingh24/contrast-model-implementation)**: Implementation of the CONTRAST architecture with training, evaluation, and visualization.

---

## Datasets

The framework was evaluated on two benchmark datasets:

| Dataset       | Train Sessions | Test Sessions | Unique Items | Avg. Session Length |
|---------------|----------------|---------------|---------------|----------------------|
| RetailRocket  | 433,643        | 15,132        | 41,762        | 5.64                 |
| Diginetica    | 719,470        | 60,858        | 37,867        | 4.06                 |

The preprocessing steps are encapsulated in the **Data Pipeline Notebook**.

---

## Performance

![Performance Table](https://github.com/user-attachments/assets/69063f0a-64d3-486d-a2b4-d6d858947d61)

---

## Running the Notebooks

To experiment with the CONTRAST model or its data pipeline:

1. Open the corresponding Kaggle notebook links.
2. Fork the notebook to your Kaggle account.
3. Run all cells (ensure GPU is enabled for faster training).

---

## License
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Licensed under the Apache License.

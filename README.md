# Automated Imbalanced Classification via Layered Learning (ICLL)

This repository provides the implementation and experimental setup for the paper:  
**"Automated imbalanced classification via layered learning"**, published in *Machine Learning* (2023).

---

## ⚠️ Maintenance Note

**This repository is not actively maintained.** For the most recent and maintained implementation of the ICLL method, please refer to the primary development repository:

-  **[vcerqueira/anomalyforecast](https://github.com/vcerqueira/anomalyforecast)**

---

## Methodology

The proposed method, **ICLL**, tackles imbalanced classification through a hierarchical, two-stage approach:

1.  **Clustering:** The data is automatically partitioned into subsets using clustering to identify specific regions of the feature space.
2.  **Layered Learning:** A two-stage classification process is applied to these subsets to improve the detection of minority class instances.



---

## Running the Experiments

To reproduce the experiments using the KEEL datasets, follow these steps:

1.  **Prepare the Data:** Unzip the `keel.zip` file located in the root directory.
2.  **Execute:** Run the main experimental script:
    ```bash
    python main.py
    ```

---

## Citation

If you use this method or code in your research, please cite the following work:

```bibtex
@article{cerqueira2023automated,
  title={Automated imbalanced classification via layered learning},
  author={Cerqueira, Vitor and Torgo, Luis and Branco, Paula and Bellinger, Colin},
  journal={Machine Learning},
  volume={112},
  number={6},
  pages={2083--2104},
  year={2023},
  publisher={Springer}
}
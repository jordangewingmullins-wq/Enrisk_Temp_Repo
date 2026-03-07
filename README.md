# Enrisk Project

This repository contains exploratory data analysis and modeling work for the Enrisk industrial AI dataset. The project focuses on understanding relationships between industrial assets, sensors, and potential failure modes, and developing models that can reason about which sensors are relevant for detecting particular failures.

## Repository Structure

* **src/** – Python source code for model training and utilities
* **notebooks/** – Jupyter notebooks used for exploratory data analysis and experiments
* **reports/** – Weekly reports and LaTeX documents
* **data/** – Local dataset files (not tracked in Git)

## Data

The dataset is not included in this repository because it should not be committed to Git. To run the notebooks, place the dataset files in the following directory:

`data/eval_data/`

**The expected files are:**
* `single_true_multi_choice_qa.jsonl`
* `multi_true_multi_choice_qa.jsonl`

## Running the Notebook

Open the notebook in the `notebooks` directory and run the cells after placing the dataset in the data folder described above.

## Authors

* Jordan Gewing-Mullins
* Matthew Jarvis

Authors

Jordan Gewing-Mullins
Matthew Jarvis

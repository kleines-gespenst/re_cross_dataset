# re_cross_dataset

Welcome to the repository for the paper "Robustness of Relation Extraction Systems: Case Study on Biographical Relation Extraction". This repository contains the documentation and resources necessary to replicate the experiments conducted in the paper.

## Overview

This repository focuses on the robustness of relation extraction (RE) systems, specifically through a case study on biographical relation extraction. It includes dataset splits, experiment configurations, and results associated with the paper.

## Data Used in the Paper

This paper uses balanced subsets of the following relation extraction datasets with biographically relevant relations:

- **TACRED**
- **TACRED-RE**
- **NYT** (10,140 instances)
- **Biographical**

The folder [dataset_splits](https://github.com/kleines-gespenst/re_cross_dataset/tree/main/dataset_splits) the dataset splits (70-20-10) with containing instance IDs used in the experiments


# TBD
## Repository Structure

- **`dataset_splits/`**: Contains the dataset splits with instance IDs for each dataset used in the experiments.
- **`scripts/`**: Includes scripts used for preprocessing the data and running the experiments.
- **`results/`**: Holds the results of the experiments, including evaluation metrics and analysis.

## Getting Started

### Prerequisites

To run the experiments, you'll need the following software installed:

- Python 3.10
- Required Python packages (listed in `requirements.txt`)

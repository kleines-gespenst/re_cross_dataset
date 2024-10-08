# re_cross_dataset

Welcome to the repository for the paper "Robustness of Relation Extraction Systems: Case Study on Biographical Relation Extraction". This repository contains the documentation and resources necessary to replicate the experiments conducted in the paper.

## Overview

This repository focuses on the robustness of relation extraction (RE) systems, specifically through a case study on biographical relation extraction. It includes dataset splits, experiment configurations, and results associated with the paper.

## Data Used in the Paper

This paper uses balanced subsets of the following relation extraction datasets with biographically relevant relations:

- [**TACRED**](https://aclanthology.org/D17-1004.pdf) subset (27,068 instances)
- [**TACRED-RE**](https://aclanthology.org/2020.acl-main.142.pdf) subset (26,993 instances): since the dev and test sets of original TACRED were revisited, some of the instances got other than biographically relevant labels => complete overlap with **TACRED** subset is therefore not possible. Still 26,993 included in **TACRED-RE** subset are also included in **TACRED** subset => relabeling results in 75 instances that are missing in **TACRED-RE** (27,068-26,993=75) since they got biographically not relevant labels.
- [**NYT**](https://link.springer.com/chapter/10.1007/978-3-642-15939-8_10) (10,136 instances): the original **NYT** dataset can be found [here](https://github.com/INK-USC/ReQuest)
- [**Biographical**](https://dl.acm.org/doi/10.1145/3477495.3531742) (20,000 instances)

The folder [dataset_splits](https://github.com/kleines-gespenst/re_cross_dataset/tree/main/dataset_splits) the dataset splits (70-20-10) with containing instance IDs used in the experiments. Since **TACRED** and **TACRED-RE** are distributed under LDC license, the desicion was made to provide only instance ids of all four dataset splits to make the experiments on the one side easily reproducible, but also to not violate the licenses.


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

### Questions & Recommendations

For any questions and recommendations, feel free to contact me by reordering @  tuwien.ac.at  varvara.arzt


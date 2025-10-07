# ExplainingCodeRisk

This repository contains datasets and evaluation results for code risk analysis research.

## Repository Structure

### Documentation
- **README.md** - This file, providing an overview of the repository contents
- **Scenarios.pdf** - Contains detailed descriptions of high and low risk scenarios used in the evaluation
- **Scenario 1-without baseline.pdf** - Output results for Scenario 1 evaluation without baseline comparisons

### Datasets
The repository includes two datasets used for the initial evaluation:

- **ant-1.7-real.csv** - Dataset from Apache Ant version 1.7 project
- **camel-1.6-real.csv** - Dataset from Apache Camel version 1.6 project

These datasets contain real-world code metrics and defect information used to evaluate code risk prediction models.

## Usage

The datasets can be used to:
- Evaluate code risk prediction models
- Reproduce experimental results
- Compare different approaches to software defect prediction

## Data Format

The CSV files contain software metrics and defect labels for classes in the respective projects. Refer to the scenarios documentation for details on how these datasets are used in different evaluation scenarios.

## Citation
D. Aggarwal, “Software defect prediction dataset,” Dataset, 2021.
[Online]. Available: https://doi.org/10.6084/m9.figshare.13536506.v1
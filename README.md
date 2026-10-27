# MyCiclo: Salivary Ferning Image Dataset 🔬

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

Welcome to the central data repository for **MyCiclo**. This open-source dataset contains anonymized, crowdsourced images of salivary ferning patterns—a biological marker of the estrogen surge preceding ovulation.

## 📊 Dataset Structure
To maintain data integrity and facilitate machine learning workflows, this repository is organized as follows:

* `/data/raw/` : Original, unmodified images captured via smartphone.
* `/data/processed/` : Cropped, normalized images ready for computer vision training.
* `/labels/annotations.csv` : Master file containing image IDs, ferning labels, and metadata.
* `/scripts/` : Utility scripts for data cleaning and exploration.

## 🔒 Privacy & Ethics
All images in this dataset have been voluntarily provided by the MyCiclo community. The data is strictly anonymized, ensuring no personally identifiable information (PII) is included, in compliance with standard biomedical data sharing protocols.

## 🤖 Model Integration
This dataset serves as the ground truth for training our predictive computer vision models. The training scripts, APIs, and deployment architectures can be found in our core codebase repository: `myciclo-ferning-models`.

## 📄 License
This dataset is released under the MIT License. We actively encourage the global health tech and research community to utilize this data to advance female reproductive autonomy.

# Toxic Comment Classification

This repository contains the code and resources for a Toxic Comment Classification model. The model is designed to classify text comments into various toxicity categories.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Results](#results)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

## Overview

The goal of this project is to build a machine learning model that can effectively classify text comments as toxic, severe toxic, obscene, threat, insult, and identity hate. The model is trained on a dataset provided by Jigsaw/Conversation AI.

## Dataset

The dataset used for training and evaluation is available on Kaggle: [Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge).

## Results

- Train Accuracy: 99.42%
- Validation Accuracy: 99.37%
- Precision: 85.26%
- Recall: 84.10%

## Usage

1. **Clone the repository:**

   ```bash
   git clone git@github.com:Ashutosh-Singh-Thakur/Toxic-Comment-Classification.git
   cd toxic-comment-classification
   ```

2. **Choose one of the following options to view and run the Jupyter Notebook:**

   - **View Locally:**
     - Install Jupyter Notebook dependencies:
       ```bash
       pip install notebook
       ```
     - Run Jupyter Notebook:
       ```bash
       jupyter notebook notebooks/toxic_comment_classification.ipynb
       ```
     - Open the notebook and run the cells to see the model in action.

   - **View on Google Colab:**
     - Click the following link to view and run the notebook on Google Colab:
       
       <a href="https://colab.research.google.com/github/Ashutosh-Singh-Thakur/Toxic-Comment-Classification/blob/main/notebooks/toxic_comment_classification.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
           
     - This will open the notebook in Google Colab, where you can run the cells and interact with the code.

## Dependencies

- Python 3.11
- Jupyter Notebook 7.0.2
- TensorFlow 2.12.0
- Keras 2.12.0
- pandas 1.5.3
- numpy 1.23.5
- matplotlib 3.7.0
- pickle 1.3.0

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to modify and use the code for your own projects. If you find it helpful, consider giving a star to the repository.

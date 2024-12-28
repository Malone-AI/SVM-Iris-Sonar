# Support Vector Machine (SVM) Classification Project

[English](README.md) | [中文](README.zh-CN.md)

## Introduction

This project utilizes Support Vector Machine (SVM) algorithms to classify the Iris and Sonar datasets. By configuring different kernel functions, it compares the performance of models across various datasets.

## Datasets

1. **Iris Dataset**: A classic dataset for multi-class classification problems.
2. **Sonar Dataset**: Sonar signal data used to distinguish between metal and rock objects.

## Project Structure

- `SVM_Iris.ipynb`: Notebook for classifying the Iris dataset using SVM.
- `SVM_Sonar.ipynb`: Notebook for classifying the Sonar dataset using SVM.

## Environment Setup

Ensure the following Python libraries are installed:

- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn

You can install dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Open the corresponding Jupyter Notebook file (e.g., `SVM_Iris.ipynb`).
2. Run each code cell sequentially to train and evaluate the SVM model.
3. View the model's classification report, confusion matrix, and ROC curve.

## Model Configuration

The project experiments with various SVM kernel configurations, including:

- Linear kernel
- Polynomial kernel (degrees 2 and 3)
- Gaussian kernel (RBF)
- Sigmoid kernel
- Laplace kernel

Performance metrics for each model will be displayed in the Notebook.

## Results

After running the Notebook, you will obtain classification reports, confusion matrices, and ROC curve images for each model, facilitating comparisons of the effectiveness of different kernel functions.

## Contribution

Contributions to the development and improvement of this project are welcome. Please submit a Pull Request or contact the maintainer.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

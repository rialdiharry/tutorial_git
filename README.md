# Tutorial Modelling Data Titanic

Tutorial ini akan mengubah data titanic menjadi data yang siap untuk dilakukan pemodelan

## Prerequisites

1. Download data [here](https://www.kaggle.com/datasets/fossouodonald/titaniccsv)
2. Install dengan "pip install requirements.txt"

## Getting Started

- Dataset Splitting
- Training
- Model Validation

### Dataset splitting

Split data into training, validation, and test sets
```code
X_train, y_train, X_test, y_test=dataset_splitting()
X_train.shape, y_train.shape
```

## References

1. Di scikit-learn documentation
# CSE475 Lab Tasks

Lab exercises for CSE475 (Machine Learning), covering regression, classical
ML algorithms, ensemble methods, unsupervised learning, and deep learning.

## Repository Structure

```
cse475-lab-tasks
├── README.md
├── regression
│   ├── task1_lung_disease.ipynb
│   └── task2_airline_satisfaction.ipynb
├── svm-decision-tree
│   ├── svm_dt_diabetes.ipynb
│   └── svm_dt_rf_cinema_ticket_sales.ipynb
├── nn-ensemble-methods
│   └── nn_svm_dt_rf_heart_disease.ipynb
├── clustering-dimensionality-reduction
│   └── kmeans_apriori_pca.ipynb
└── cnn
    └── cnn_cifar10_classification.ipynb
```

## Contents

 Folder  Notebook  Topic  Dataset 
------------
 `regression`  `task1_lung_disease.ipynb`  Preprocessing, EDA, logistic regression  Lung disease 
 `regression`  `task2_airline_satisfaction.ipynb`  Preprocessing, EDA, linear regression  Airline customer satisfaction 
 `svm-decision-tree`  `svm_dt_diabetes.ipynb`  SVM and Decision Tree  Diabetes 
 `svm-decision-tree`  `svm_dt_rf_cinema_ticket_sales.ipynb`  SVM, Decision Tree, Random Forest, hyperparameter tuning  Cinema ticket sales 
 `nn-ensemble-methods`  `nn_svm_dt_rf_heart_disease.ipynb`  Neural Network, SVM, Decision Tree, Random Forest comparison  Heart disease (UCI) 
 `clustering-dimensionality-reduction`  `kmeans_apriori_pca.ipynb`  K-means clustering, Apriori association rules, PCA  Mall Customers, Groceries, Iris 
 `cnn`  `cnn_cifar10_classification.ipynb`  CNN image classification with VGG19, DenseNet121, EfficientNetB0  CIFAR-10 

## Requirements

- Python 3.9+
- Jupyter Notebook or JupyterLab
- pandas, NumPy, Matplotlib, seaborn
- scikit-learn
- mlxtend (Apriori, in `clustering-dimensionality-reduction`)
- TensorFlow  Keras (in `nn-ensemble-methods` and `cnn`)

```bash
pip install pandas numpy matplotlib seaborn scikit-learn mlxtend tensorflow jupyter
```

## Running the Notebooks

1. Clone the repository and open a notebook from inside its own folder, so the
   dataset paths resolve.
2. Run the cells from top to bottom.

The CIFAR-10 dataset used in `cnn` is downloaded automatically by Keras on the
first run. A GPU is recommended for that notebook.

## Notes

- The CNN notebook is a quick demonstration run images resized to 96x96, a
  subset of the training data, 5 epochs, and frozen pretrained backbones.
- Datasets are the course-provided or public datasets listed above.

## Author

**Kaniz Reza Mithila**
Department of Computer Science, East West University, Dhaka, Bangladesh
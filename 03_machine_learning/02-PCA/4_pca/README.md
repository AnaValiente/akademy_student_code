# Principal Component Analysis
During this session you will learn what is PCA, how to implement it and which are its main applications.

## Lecture
You can find the slides for this lecture in the folder `lecture/`.
The topics covered by this lecture are:
- Dimensionality reduction
- Principal Component Analysis: overview
- Principal Component Analysis: example
- Principal Component Analysis: the algorithm
- Covariance and covariance matrix
- Covariance vs. Correlation
- PCA vs. LDA
- PCA as dimensionality reduction
- PCA applications

After the lecture, we will have a live coding demo on how to apply PCA to the titanic dataset. The notebook used for the live coding demo (`01_LivecodingDemo_Titanic_PCA.ipynb`), can be found in the folder `exercises/`.
During the live coding demo we will cover the following aspects:
- Loading the dataset
- Preprocessing the data:
  - Encoding the features (label encoding vs. binary/dummy encoding)
  - Handling missing values
  - Dropping not relevant features
  - Creating new features from the existing features
  - Discretizing the continuous features (from continuous to ranges)
- Training a model without PCA
- Applying PCA
- Training different models after applying dimensionality reduction with PCA

## Homework
The exercises to be done for this topic can be found in the folder `exercises/`.

The exercises for today are the following:
- Read the notebook `00_PCA_applications.ipynb`, which contains an overivew of different applications of PCA
- Apply PCA on the Iris dataset
- Apply LDA on the Iris dataset
- Read the notebook `02_Pandas_Built_in_Data_Visualization.ipynb`, which is a tutorial on Pandas Visualization
- Solve the exercises on the notebook `03_Pandas_Data_Visualization_Exercise .ipynb`
- Solve the exercises on the notebook `04_Breast_Cancer_PCA.ipynb` (we will correct this exercise in class)
- (Optional) Apply PCA on the Iris dataset using just `numpy` and compare the result with the ones obtained with Scikit-learn (you should obtain the same results)

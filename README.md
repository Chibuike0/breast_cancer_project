**"Breast_cancer_project"**

The aim of this project was to use build a classification model that predict cancer, then use Streamlit to deploy the model for other users interaction with the model. THe entire project was used on VScode and a venv enviroment was created to achieve consistent deployment. 
Within the enviroment, an experiment.ipynb was created. Here the codes for data preprocessing, visualization, model building, hyperparameter tuning and conclusion are situated.
The Prediction.ipynb is where local prediction using the built model was tested before deployment. Lastly App.py file is where streamlit was activated for local deplyment.

**DATASET INFORMATION**
id: Unique identifier for each entry (int64).

diagnosis: Diagnosis of the breast cancer (M = malignant, B = benign) (object).

radius_mean: Mean radius of the tumor (float64).

texture_mean: Mean texture of the tumor (float64).

perimeter_mean: Mean perimeter of the tumor (float64).

area_mean: Mean area of the tumor (float64).

smoothness_mean: Mean smoothness of the tumor (float64).

compactness_mean: Mean compactness of the tumor (float64).

concavity_mean: Mean concavity of the tumor (float64).

concave points_mean: Mean number of concave points of the tumor (float64).

symmetry_mean: Mean symmetry of the tumor (float64).

fractal_dimension_mean: Mean fractal dimension of the tumor (float64).

radius_se: Standard error of the radius (float64).

texture_se: Standard error of the texture (float64).

perimeter_se: Standard error of the perimeter (float64).

area_se: Standard error of the area (float64).

smoothness_se: Standard error of the smoothness (float64).

compactness_se: Standard error of the compactness (float64).

concavity_se: Standard error of the concavity (float64).

concave points_se: Standard error of the number of concave points (float64).

symmetry_se: Standard error of the symmetry (float64).

fractal_dimension_se: Standard error of the fractal dimension (float64).

radius_worst: Worst (largest) radius (float64).

texture_worst: Worst texture (float64).

perimeter_worst: Worst perimeter (float64).

area_worst: Worst area (float64).

smoothness_worst: Worst smoothness (float64).

compactness_worst: Worst compactness (float64).

concavity_worst: Worst concavity (float64).

concave points_worst: Worst number of concave points (float64).

symmetry_worst: Worst symmetry (float64).

fractal_dimension_worst: Worst fractal dimension (float64).

Written by Chibuike


# Heart Disease Risk Assessment

This project aims to predict the risk of heart disease in individuals using machine learning models. The dataset contains various health and medical attributes that are processed and analyzed to determine patterns and correlations, enabling the prediction of heart disease. The project employs techniques such as feature selection, data visualization, and classification using algorithms like K-Nearest Neighbors (KNN) and Random Forest.




## Tools and Libraries Used

Python Libraries:

a) numpy and pandas: For data manipulation and numerical computations.

b) matplotlib and seaborn: For data visualization.

c) scikit-learn: For machine learning models and preprocessing.

Other Tools:

a) Jupyter Notebook: For interactive coding and visualization.
## Tools and Libraries Used

Python Libraries:

a) numpy and pandas: For data manipulation and numerical computations.

b) matplotlib and seaborn: For data visualization.

c) scikit-learn: For machine learning models and preprocessing.

Other Tools:

a) Jupyter Notebook: For interactive coding and visualization.
## Dataset

The dataset used for this project includes various features related to heart health, such as:

* Age

* Sex

* Chest pain type (cp)

* Resting blood pressure (trestbps)

* Serum cholesterol (chol)

* Fasting blood sugar (fbs)

* Maximum heart rate achieved (thalach)

* Oldpeak (ST depression induced by exercise)

* Target: Indicates the presence (1) or absence (0) of heart disease.

## Project Workflow

1. Exploratory Data Analysis (EDA)

* Displayed dataset information and summary statistics using df.info() and df.describe().

* Visualized feature correlations using a heatmap.

* Examined the target variable distribution using a count plot.

* Visualized feature distributions with histograms.

2. Feature Selection

* Calculated the correlation matrix to identify important features.

* Plotted a heatmap to visualize correlations between features.

3. Data Processing

* Applied one-hot encoding to categorical features such as sex, cp, fbs, restecg, exang, slope, ca, and thal using pd.get_dummies.

* Standardized numerical features like age, trestbps, chol, thalach, and oldpeak using StandardScaler from scikit-learn.

4. Model Training and Evaluation   
K-Nearest Neighbors (KNN):

* Evaluated the KNN model for various values of K using cross-validation.

* Plotted KNN scores for different values of K to select the optimal K.

* Achieved the best performance with K = 12.

Random Forest:

* Trained a Random Forest classifier with 10 estimators.

* Evaluated the model using 10-fold cross-validation.

5. Results

KNN Classifier: Achieved a mean cross-validation score of 85.07% .

Random Forest Classifier: Achieved a mean cross-validation score of 81.99% .
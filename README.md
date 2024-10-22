# Machine Learning-Based Water Potability Prediction

## Aim of the Project
This project predicts the potability of water based on various water quality features using machine learning algorithms. The goal is to classify water samples as either potable (safe to drink) or non-potable based on features like pH, Hardness, and Chloramines.

## Dataset
- **Dataset Name**: Water Quality Dataset
- **Features**: `pH`, `Hardness`, `Solids`, `Chloramines`, `Sulfate`, `Conductivity`, `Organic Carbon`, `Trihalomethanes`, `Turbidity`
- **Target**: `Potability` (binary: 0 = non-potable, 1 = potable)

## How to Run the Code
1. Download `202231570_DSPML_CODE_MIDTERM-PROJECT.ipynb` notebook file as well as the `water_potability.csv` dataset.
2. Open the project file in **Jupyter Notebook** via **Anaconda**.
3. Simply open the `202231570_DSPML_CODE_MIDTERM-PROJECT.ipynb` notebook file.
4. Click on `Run All` in Jupyter Notebook to execute the code automatically.
   - All necessary libraries and dependencies are handled within the environment.

## Dependencies
The dependencies for my project, are the following Python libraries:

1. **numpy** - For numerical operations and arrays.
2. **pandas** - For data manipulation and analysis.
3. **matplotlib** - For creating visualizations.
4. **seaborn** - For statistical data visualization.
5. **scikit-learn** - For machine learning models, data preprocessing, and evaluation metrics.
6. **imbalanced-learn** - For handling imbalanced datasets (used for SMOTE).
   - These dependencies except imbalanced-learn is pre-installed in your Anaconda environment if you're using Jupyter Notebook.

## Project Steps
1. **Exploratory Data Analysis (EDA)**
   - Data inspection, visualizations (heatmaps, distributions, box plots).
2. **Data Preprocessing**
   - Handle missing values and balance the dataset using SMOTE.
   - Scale features for better model performance.
3. **Model Training and Evaluation**
   - Trained various machine learning models (e.g., Extra Trees, K-Nearest Neighbors, Naive Bayes, etc.).
   - Evaluated using accuracy, precision, recall, and F1-score.
4. **Hyperparameter Tuning**
   - Tuned the Extra Trees Classifier for optimal performance.

## Results
- The **Extra Trees Classifier** achieved the best performance with a test accuracy of **66.31%** after hyperparameter tuning.
- The precision-recall trade-off showed balanced results for predicting potable water.

## Contact
For any questions, feel free to reach out to:

- **Name**: Loyola, Jeed Ashley H.
- **Email**: LJH1570@dlsud.edu.ph
- **Course**: ECE31 - Digital Signal Processing Machine Learning Lab
- **Professor**: Engr. Mark Montances

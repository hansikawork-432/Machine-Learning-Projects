# Machine Learning Projects

Welcome to my dedicated Machine Learning repository. This space serves as a centralized portfolio and testing ground for my hands-on implementations in data science, classical machine learning, and deep learning.

The primary focus of this repository is transforming raw data into optimized, predictive pipelines while applying mathematical theory to real-world datasets.

---

## Tech Stack & Ecosystem

* **Languages:** Python, SQL
* **Data & Visualization:** Pandas, NumPy, Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn, SciPy, XGBoost, LightGBM
* **Deep Learning & Frameworks:** PyTorch / TensorFlow

---

## Repository Structure

The code is organized categorically by paradigm to ensure clean navigation:

* `01-supervised-learning/` – Regression and Classification pipelines.
* `02-unsupervised-learning/` – Clustering, Dimensionality Reduction, and Anomaly Detection.
* `03-deep-learning/` – Neural Network architectures and modern AI applications.
* `data/` – Compressed datasets and data loading utilities.

---

## Projects Index

| Project Link | Paradigm / Domain | Key Tech & Features | Status |
| :--- | :--- | :--- | :--- |
| **[Insurance-Charges-Prediction]** | Regression | Pandas, SciPy (`pearsonr`), Scikit-Learn (`StandardScaler`) | Preprocessing & EDA |


---

## Detailed Project Breakdowns

### 1. Insurance Charges Prediction
**Objective:** Clean, engineer, and scale historical healthcare metrics to isolate structural drivers of patient medical costs.

#### Phase Breakdowns Present in the Notebook
* **Exploratory Data Analysis (EDA):**
  * Distribution analysis of continuous features (`Age_Years`, `Body_Mass_Index`, `Children`, `Cost`) using Seaborn `histplot` and `boxplot`.
  * Categorical frequency visualizations via `countplot`.
  * Initial multi-variable interaction tracking with a numerical correlation heatmap.
* **Data Cleaning:**
  * Verifying structural integrity (`shape`, `info`, and tracking `isnull().sum()`).
  * Removing duplicate data rows via `drop_duplicates()`.
* **Feature Engineering & Preprocessing:**
  * Binary integer mapping for `Gender` (male: 0, female: 1) and `Smoking_Status` (yes: 0, no: 1).
  * One-Hot Encoding (`pd.get_dummies`) for geographical categories (`Geo_Region`) with dummy variable dropping to avoid multicollinearity.
  * Custom interval binning (`pd.cut`) of continuous BMI data into a new tracking variable (`bmi_category`) followed by dummy mapping.
  * Feature scaling and standardization using Scikit-Learn's `StandardScaler` on continuous inputs.
* **Statistical Feature Selection:**
  * Quantifying linear relationships using **Pearson Correlation Coefficients** (`pearsonr`) explicitly mapping independent feature influences against the target column (`Cost`).

---

## Connect with Me

If you have any questions or want to discuss machine learning engineering, feel free to connect!

* **LinkedIn:** [Your Name](https://linkedin.com/in/hansika-207907385)


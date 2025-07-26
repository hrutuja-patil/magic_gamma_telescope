# 🌌 Magic Gamma Telescope - Particle Classification Project

This project focuses on building a machine learning model to classify particles as **gamma** or **hadron** based on observational data from the MAGIC Gamma Telescope.

---

## 📂 Project Structure


---

## 🧪 Dataset

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/magic+gamma+telescope)
- **Attributes**: 10 continuous features extracted from high-energy gamma particle showers
- **Target**: `'g'` for gamma and `'h'` for hadron

---

## ⚙️ Technologies Used

- Python 3.x
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

---

## 📊 Steps Performed

1. **Data Loading and Cleaning**
   - Handled missing values (if any)
   - Converted labels to numerical form (gamma = 1, hadron = 0)

2. **Exploratory Data Analysis (EDA)**
   - Histogram and distribution plots
   - Correlation matrix

3. **Model Training**
   - Trained multiple models: Logistic Regression, Decision Tree, Random Forest, SVM
   - Used accuracy, precision, recall, and F1-score as evaluation metrics

4. **Model Tuning**
   - Performed Grid Search for hyperparameter optimization

5. **Results**
   - Compared performance of models
   - Identified the best-performing classifier

---

## 🔍 How to Run

1. Clone the repository
2. Open `sample.ipynb` in Jupyter
3. Run all cells to see analysis and model results

```bash
git clone https://github.com/hrutuja-patil/magic_gamma_telescope.git
cd magic_gamma_telescope
jupyter notebook sample.ipynb

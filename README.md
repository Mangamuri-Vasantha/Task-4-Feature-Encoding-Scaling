# Task-4-Feature-Encoding-Scaling
# Task 4: Feature Encoding & Scaling – Adult Income Dataset

## 📌 Objective  
The goal of this task is to preprocess the Adult Income Dataset by applying feature encoding and scaling techniques to make the data suitable for machine learning models.

---

## 🛠 Tools Used  
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## 📂 Dataset  
- **Adult Income Dataset (`adult.csv`)**  
This dataset contains demographic and employment-related information used to predict whether a person earns more than $50K per year.

---

## 🔄 Steps Performed  

1. **Loaded the Dataset**  
   - Read the CSV file using Pandas.  
   - Displayed basic information and sample rows.

2. **Identified Feature Types**  
   - Separated columns into:
     - Categorical features  
     - Numerical features  

3. **Label Encoding**  
   - Applied Label Encoding to the `education` column since it has an inherent order.

4. **One-Hot Encoding**  
   - Applied One-Hot Encoding to all remaining categorical features that do not have an order.

5. **Feature Scaling**  
   - Scaled all numerical features using `StandardScaler` to standardize the data.

6. **Verification**  
   - Compared numerical values before and after scaling to confirm transformation.

7. **Saved Processed Dataset**  
   - Exported the final preprocessed dataset as `adult_preprocessed.csv`.

---

## 📁 Output Files  

- `Adult Income Notebook.ipynb` – Jupyter Notebook with all preprocessing steps  
- `adult.csv` – Original dataset  
- `adult_preprocessed.csv` – Final preprocessed dataset  

---

## ✅ Final Outcome  

- Categorical features successfully encoded  
- Numerical features scaled  
- Dataset made ready for machine learning models  

---

## 📚 Key Concepts Learned  

- Difference between Label Encoding and One-Hot Encoding  
- Importance of feature scaling  
- When and why to use StandardScaler  
- Basic feature engineering workflow  

---
 

# Ridge vs Lasso Regression Comparison

## 📌 Project Overview
Performance comparison of Ridge (L2) and Lasso (L1) regression models on the Diabetes dataset.  
**Objective:** Identify the most effective regularization method for blood glucose level prediction.

![Ridge vs Lasso Coefficients](Lasso%40vs%40Ridge/results/RvsL.png)

## 🚀 Key Features
- Data preprocessing pipeline
- Hyperparameter optimization with GridSearchCV
- Coefficient analysis and visualization
- Model performance comparison

## 📊 Dataset Information
**Source:** diabetes_clean.csv (768 samples)  
**Target Variable:** glucose (blood glucose level)

**Key Features:**
- pregnancies
- diastolic (blood pressure)
- triceps (skin thickness)
- diabetes (diagnosis)
- age
- bmi

## 🧠 Model Details

### Optimized Parameters
| Model  | Best Alpha | 
|--------|------------|
| ![Ridge](https://img.shields.io/badge/Ridge-1-blue) | 1 |
| ![Lasso](https://img.shields.io/badge/Lasso-0.1-orange) | 0.1 |

### Coefficient Comparison
| Feature      | Ridge     | Lasso     |
|--------------|-----------|-----------|
| diabetes     | 24.87     | 24.60     |
| dpf          | 1.70      | 0.81      |
| age          | 0.49      | 0.49      |
| pregnancies  | -0.46     | -0.45     |

## 📈 Key Results
- **Ridge:** Balanced shrinkage while retaining all features
- **Lasso:** 52% coefficient reduction for `dpf` feature
- **Common Finding:** `diabetes` is the strongest predictor

## 🛠️ Installation
```bash
git clone https:/barisgudul/Ridge_vs_Lasso_Analysis.git
cd Ridge_vs_Lasso_Analysis
```
## 🖥️ Usage

```bash
# Run the analysis script
python LvsR.ipynb
```
## 📄 License

**MIT License**  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Permissions:**  
✅ Free academic/research use  
✅ Modification and redistribution  
❌ Commercial use requires written consent  

Full license terms available in [LICENSE](LICENSE) file.

---

## 📧 Contact Information

**Project Maintainer**  
[![Author Badge](https://img.shields.io/badge/Author-barisgudul-blue.svg)]()  
[![Email](https://img.shields.io/badge/Email-mehmetbarisgudul@gmail.com-red.svg)](mailto:mehmetbarisgudul@gmail.com)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-informational.svg)](https://linkedin.com/in/mehmet-baris-gudul-1101bg)

**Contribution Guidelines:**  
We welcome collaborations! Please reach out via email before submitting PRs.

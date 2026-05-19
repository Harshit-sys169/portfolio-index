Data Science & ML Portfolio
===========================

A comprehensive portfolio of data science, machine learning, and financial analysis projects. Each project is maintained in its own repository for clarity and modularity.

**Portfolio Overview** | **[GitHub Profile](https://github.com/Harshit-sys169)**

---

Projects
--------

### 1. A/B Testing & Statistical Analysis  
**Repository:** [ab-testing-wqu](https://github.com/Harshit-sys169/ab-testing-wqu)  
Statistical hypothesis testing and experimental design for applicant engagement strategies.

**Key Skills:** Power analysis, Chi-square testing, Hypothesis testing, MongoDB integration, Geographic visualization

**Highlights:**
- Calculated statistical power and required sample sizes
- Chi-square tests for statistical significance
- Contingency table analysis with odds ratios
- Geographic choropleths for result visualization

---

### 2. Buenos Aires Real Estate Price Prediction  
**Repository:** [buenos-aires-real-estate](https://github.com/Harshit-sys169/buenos-aires-real-estate)  
Progressive real estate analysis from basic regression to advanced ensemble methods.

**Key Skills:** Regularization (Ridge/Lasso/ElasticNet), Feature selection (SelectKBest/RFE/Permutation), Model stacking, Cross-validation

**Highlights:**
- Task 1-3: Progressive complexity (linear → geographic → neighborhood features)
- Task 4 Advanced: Regularization comparison with 4 different techniques
- Task 4 Feature Selection: 4 methods (SelectKBest, RFE, Lasso, Permutation importance)
- Task 4 Model Stacking: Ensemble blending of diverse base learners
- Demonstrated coefficient behavior and sparsity analysis

---

### 3. Credit Risk Analysis  
**Repository:** [credit-risk-clustering](https://github.com/Harshit-sys169/credit-risk-clustering)  
Unsupervised learning for business owner financial segmentation.

**Key Skills:** K-Means clustering, PCA dimensionality reduction, Silhouette analysis, Feature standardization

**Highlights:**
- Optimal cluster selection using silhouette analysis
- PCA for 2D visualization of high-dimensional data
- Cluster profiling and business interpretation
- Understanding cluster characteristics in original feature space

---

### 4. Earthquake Damage Prediction (Advanced ML Methodology)  
**Repository:** [earthquake-damage-prediction](https://github.com/Harshit-sys169/earthquake-damage-prediction)  
Production-grade classification with rigorous methodology: hyperparameter optimization, feature importance, CV strategy.

**Key Skills:** 
- GridSearchCV with StratifiedKFold
- Hyperparameter tuning (max_depth, min_samples, criterion)
- Tree-based and permutation importance
- Feature group analysis with business interpretation
- Imbalanced data handling (stratified splitting)
- Comprehensive cross-validation strategy explanation

**Highlights:**
- Three-way stratified split (train/val/test) preserving class distribution
- GridSearchCV optimization for Decision Trees and Logistic Regression
- Multiple feature importance methods (tree-based + permutation)
- Feature groups analysis: Age, Size, Foundation, Structure, Configuration
- Cross-validation strategy documentation with stability analysis
- F1 score optimization for imbalanced data (not accuracy)

---

### 5. Bankruptcy Prediction in Poland (Advanced Techniques)  
**Repository:** [bankruptcy-prediction-poland](https://github.com/Harshit-sys169/bankruptcy-prediction-poland)  
End-to-end ML project with advanced techniques for imbalanced data, ensemble methods, SHAP interpretability, and cost-aware optimization.

**Key Skills:**
- Imbalanced data handling (SMOTE, Random Oversampling)
- Ensemble methods (Random Forest, Gradient Boosting, AdaBoost)
- Cost-sensitive learning with threshold optimization
- SHAP model interpretability
- Business metrics and financial impact analysis
- Proper evaluation metrics (F1, ROC-AUC, Balanced Accuracy)

**Highlights:**
- Demonstrated why accuracy fails on imbalanced data
- Compared multiple imbalance handling techniques
- Ensemble comparison showing diversity advantage
- SHAP values for prediction-level explanations
- Cost curves for threshold optimization
- Business impact analysis translating model predictions to financial value

---

### 6. Market Volatility Analysis  
**Repository:** [market-volatility-analysis](https://github.com/Harshit-sys169/market-volatility-analysis)  
Financial time series analysis for volatility patterns and market trends.

**Key Skills:** Time series processing, Rolling statistics, Volatility metrics, Market visualization

**Highlights:**
- Rolling volatility calculation
- Exponentially weighted moving averages
- Drawdown analysis
- Risk-return visualization

---

### 7. Latin America Real Estate Markets  
**Repository:** [latin-america-real-estate](https://github.com/Harshit-sys169/latin-america-real-estate)  
Real estate analysis across Brazil and Mexico with feature engineering focus.

**Key Skills:** Geographic data processing, Feature engineering, Missing value handling, Preprocessing pipelines

**Highlights:**
- Coordinate extraction from location strings
- Hierarchical location parsing
- ColumnTransformer for mixed feature types
- Geographic aggregation and neighborhood analysis

---

Portfolio Competencies
======================

**Machine Learning & Statistics**
- Regression: Linear, Ridge, Lasso, ElasticNet
- Classification: Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, AdaBoost
- Clustering: K-Means, PCA
- Ensemble methods and model stacking
- Hyperparameter optimization with GridSearchCV
- Cross-validation strategies (K-Fold, StratifiedKFold)

**Data Science & Engineering**
- Data cleaning and preprocessing
- Feature engineering and selection
- Handling missing values and outliers
- Working with multiple data sources (CSV, JSON, SQLite, MongoDB)
- Building reusable ML pipelines

**Handling Real-World Challenges**
- Imbalanced data: SMOTE, oversampling, appropriate metrics
- Class imbalance: Stratified splitting, cost-sensitive learning
- High-dimensional data: PCA, feature selection
- Messy data: Missing values, outliers, inconsistent formats
- Business constraints: Cost asymmetry, threshold optimization

**Model Interpretation & Communication**
- Feature importance (tree-based, permutation)
- SHAP values for model explanations
- Confusion matrix analysis
- ROC and Precision-Recall curves
- Business metric translation

**Visualization & Communication**
- Static plots: matplotlib, seaborn
- Interactive visualizations: plotly
- 3D surface plots for geographic data
- Confusion matrices and feature importances
- Geographic choropleths

---

Technology Stack
================

**Core ML & Data**
- Python, pandas, numpy, scikit-learn
- imblearn (SMOTE, imbalanced data)
- scipy, statsmodels (statistical analysis)

**Specialized Libraries**
- SHAP (model interpretability)
- category_encoders (advanced encoding)
- yfinance (financial data)

**Databases & Data Handling**
- SQLite, MongoDB
- SQLAlchemy
- JSON processing

**Visualization**
- matplotlib, seaborn
- plotly (interactive)
- country_converter (geographic)

---

Key Learnings & Philosophy
==========================

1. **Methodology > Algorithm:** Proper train/test splitting, cross-validation, and hyperparameter tuning matter more than fancy algorithms.

2. **Business Reality:** Statistics don't drive decisions; business metrics do. Understanding misclassification costs and ROI is critical.

3. **Imbalanced Data is the Norm:** Most real ML problems are imbalanced. Standard accuracy is misleading.

4. **Ensemble Diversity Wins:** Combining different model types (linear + tree-based) beats tuning a single model.

5. **Interpretability Drives Adoption:** SHAP, feature importance, and business translations are essential for stakeholder buy-in.

6. **Feature Engineering Drives Performance:** Domain understanding and feature engineering often beat algorithm tuning.

7. **Proper Evaluation is Non-Negotiable:** CV estimates are more reliable than single train/test splits.

---

Project Statistics
==================

- **Total Projects:** 7
- **Repositories:** 8 (including this index)
- **Advanced Techniques:** Ensemble methods, SHAP, Cost-sensitive learning, Feature selection, Hyperparameter optimization
- **Domains:** Finance, Real Estate, Earthquake, Bankruptcy, A/B Testing, Market Analysis
- **Focus Areas:** Production-grade methodology, Business-aware ML, Model interpretability

---

Getting Started
===============

Each project is self-contained with its own:
- `README.md` - Detailed project documentation
- `requirements.txt` - Python dependencies
- Analysis scripts - Ready to run (with data)

**To explore:**
1. Choose a project from the list above
2. Click the repository link
3. Clone: `git clone <repository-url>`
4. Install: `pip install -r requirements.txt`
5. Run: `python <script-name>.py`

---

Contact & Links
===============

- **GitHub:** [@Harshit-sys169](https://github.com/Harshit-sys169)
- **Portfolio Index:** This repository
- **Individual Projects:** See links above

Interested in data science, machine learning, quantitative finance, or these projects? Let's connect!

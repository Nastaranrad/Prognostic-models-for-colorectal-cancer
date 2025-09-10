
# Prognostic models for colorectal cancer recurrence using carcinoembryonic antigen measurements

This project investigates the use of machine learning models to predict **colorectal cancer (CRC) recurrence** based on carcinoembryonic antigen (CEA) levels. The approach demonstrates how both static and temporal biomarker features can be leveraged to support early detection of recurrence and guide clinical decision-making.

---

## Method Summary

- **Dataset & Features**  
  - Serial CEA measurements were collected from CRC patients during follow-up.  
  - Two main categories of features were engineered:  
    - **Static features**: single-value summaries such as mean, maximum, minimum, baseline level, etc.  
    - **Temporal features**: dynamic characteristics such as slope (rate of change), variability, and differences between consecutive values.  

- **Modeling Approach**  
  - Several machine learning classifiers were implemented, including Logistic Regression, Random Forest, Gradient Boosting, and Support Vector Machines.  
  - Models were trained and tested on the dataset, and their performance was compared.  
  - Evaluation metrics included accuracy, sensitivity, specificity, and AUC.  

---

## Results and Visualization

### Classifier Performance (Figure 2)  
Different classifiers showed variability in predictive performance. Ensemble-based methods (e.g., Random Forest, Gradient Boosting) outperformed traditional baselines in recurrence prediction.  

![Figure 1: Results](figures/results.png)

### Feature Importance of Static Features (Figure 3)  
Feature importance analysis was conducted on the **static features**. These findings highlight the predictive value of specific static characteristics in addition to temporal trends.  

![Figure 1: Feature Importance](figures/featureImportance.png)




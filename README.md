# Model 862 – Patient-Specific Seizure Prediction Using LSTM (European iEEG Dataset)

This project presents a patient-specific seizure prediction model using intracranial EEG (iEEG) data from the **European iEEG dataset**, focusing on **Patient 862**. The analysis is part of a larger study conducted across **26 patients**, with the goal of developing lightweight and reliable models optimized for **wearable and implantable devices**.

## 📊 Project Overview

Our model follows a multi-step pipeline (illustrated in the accompanying figure) that includes signal preprocessing, feature extraction, and classification using various LSTM-based architectures. To evaluate the trade-off between **model complexity and performance**, we tested **five different model configurations**.

## 🔍 Results for Patient 862

- **Patient Profile**: 16-year-old female with a 4-year seizure history  
- **Seizure Type**: All recorded seizures are **secondarily generalized**  
- **Subclinical Seizures**: None reported, contributing to model performance  

### ✅ Best Performing Model (Model-1)

| Metric       | Value    |
|--------------|----------|
| AUC          | **1.00** |
| False Positive Rate (FPR) | **0.01** |
| Accuracy     | **99.2%** |

Model-1 demonstrated exceptional predictive performance for Patient 862. The absence of subclinical seizures and the presence of consistent seizure types contributed to this result.

## 📚 Related Publications

This project is based on and supported by the following research publications:

1. [**A Study on iEEG-Based Epileptic Seizure Prediction Using Patient-Specific and General Models**  
   *IEEE Access*](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=skl7eewAAAAJ&citation_for_view=skl7eewAAAAJ:Tyk-4Ss8FVUC)

2. [**Analysis of Seizure Type and Age in Epileptic Seizure Prediction**  
   *Bioengineering*](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=skl7eewAAAAJ&citation_for_view=skl7eewAAAAJ:IjCSPb-OGe4C)

3. [**Power-Efficient Deep Learning Model for Wearable and Implantable Epileptic Seizure Systems**  
   *IEEE Transactions on Biomedical Circuits and Systems*](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=skl7eewAAAAJ&citation_for_view=skl7eewAAAAJ:qjMakFHDy7sC)

These works explore the relationship between model performance, seizure type, patient demographics, and system design considerations.

## ⚙️ Tools and Technologies

- **Python 3.x**
- **PyTorch**
- **NumPy**, **Pandas**
- **Matplotlib**, **Seaborn**
- Jupyter Notebook (Anaconda environment)

## 📁 Files

- `Model_862.ipynb`: Main notebook with model development, training, evaluation, and visualizations  
- Supporting figures and data are integrated within the notebook  

## 💡 Research Context

This work is part of a broader study aiming to understand how factors like **patient age, gender, and seizure type** influence model performance. Our goal is to bridge the gap between **engineering models** and **clinical relevance** in seizure prediction systems.

## 📬 Contact

If you have questions or are interested in collaboration, feel free to reach out:  
**Shiva Maleki Varnosfaderani**  
📧 shiva.maleki@wayne.edu  
🔗 [LinkedIn](https://www.linkedin.com/in/shiva-maleki-varnosfaderani) | [Website](https://sites.google.com/view/shivamalekivarnosfaderani)

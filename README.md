# Hurricane Impacts on Shipping Lanes and Vessels
Marsh McLennan AI Studio Project for Break Through Tech

## Purpose

This project aims to predict the impact of hurricanes on vessel traffic along the US East Coast, with a focus on understanding how hurricanes influence vessel behavior and port closures. By linking vessel routes to hurricane paths and identifying disruptions, the project provides valuable insights for supply chain resilience. The ultimate goal is to help stakeholders, such as manufacturers and retailers, plan for and mitigate the effects of hurricanes on critical cargo shipments.

---

## Project Overview, Objectives, and Goals

The project addresses the challenge of predicting vessel behavior during hurricanes to improve visibility over the supply chain in the context of natural disasters. It aims to:
- Link vessel routes to hurricane paths.
- Identify behavioral patterns in vessels affected by hurricanes.
- Develop a machine learning model to predict vessel movements during hurricanes, enhancing preparedness and minimizing disruptions.

The project is critical because disruptions in shipping caused by hurricanes can significantly impact operations and profits in interconnected value chains.

---

## Methodology

### Data Collection and Preparation
- **Hurricane Data:** HURDAT2 dataset of tropical cyclones, including coordinates, wind speeds, and pressure every six hours.
- **Vessel Data:** AIS dataset recording vessel locations, compass bearings, dimensions, and types.
- Data cleaning involved merging datasets by timestamps, removing duplicates, and creating labels like `PathChange` to indicate vessel status.

### Modeling and Algorithms
- Several algorithms were tested, including Random Forest, Logistic Regression, SVM, and K-Nearest Neighbor.
- The target variable was `PathChange`, with a stratified train-test split ensuring balanced representation.
- A Random Forest model was fine-tuned using Grid Search to optimize hyperparameters like `n_estimators`, `max_depth`, and `min_samples_split`.

---

## Results and Key Findings

- **Insights:** Hurricanes weaken as they approach the East Coast. Larger vessels typically deviate about 10 degrees daily, with significant deviations often indicating hurricanes.
- **Model Performance:** The Random Forest model outperformed other algorithms, achieving the highest accuracy. Precision, recall, and confusion matrices were used for evaluation.
- **Key Discovery:** Vessels are significantly more likely to veer off course during hurricanes, highlighting the importance of predictive modeling in disaster scenarios.

---

## Visualizations

Visual representations included:
- Confusion matrices for model evaluation.
- ROC curves for the Random Forest model.

![Screenshot 2024-11-24 at 8 07 12 PM](https://github.com/user-attachments/assets/ab7f8b26-a179-4e3e-97c6-c29b0e0c6492)

---

## Potential Next Steps

- Fine-tuning the Random Forest model through hyperparameter optimization.
- Experimenting with feature selection to improve predictive accuracy.
- Saving the trained model using Pickle for deployment and further analysis.

---

# Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Tech Stack](#technology)
- [Credits and Acknowledgments](#credits-and-acknowledgments)

---

# Installation

## Step 1: Clone the Repository
Run the following command to clone the project repository to your local machine:

```
git clone <repository_url>
```
Replace `<repository_url>` with the actual URL of the repository.

---

# Usage

The project consists of two main folders: `datasets` and `notebooks`.

- **`datasets` Folder**: This folder contains the dataset required for training and experimenting with models. Ensure the dataset is properly set up before running the notebooks.

- **`notebooks` Folder**: This folder contains Jupyter notebooks for experimenting with the data and training models. If you're looking to get started, we recommend exploring the modeling notebooks, where you can tweak parameters, train a model on the provided dataset, and evaluate its performance.

---

# Technology

### Tech Stack
- VS Code (Jupyter Notebook Extension)
- GitHub/Git
- Python
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
    
---

# Credits and Acknowledgments

### Contributers
- Jawad Rada
- Enrista Ilo
- Ruth Velasquez
- Samantha Quan

### Advisors
- **AI Studio TA:** Saksham Mohan
- **Challenge Advisor:** Omar Aboubakr

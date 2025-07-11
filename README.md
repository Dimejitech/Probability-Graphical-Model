# 🧠 Bayesian Network for Medical Risk Prediction

This project demonstrates how to build and visualize a **Probabilistic Graphical Model (PGM)** — specifically a **Bayesian Network** — using synthetic medical data. It simulates relationships between health-related variables such as **age**, **smoking habits**, **exercise**, and the likelihood of developing **heart disease**. The model is implemented entirely within a single Jupyter Notebook, using only core Python libraries. It is ideal for educational purposes and for anyone looking to understand the foundations of Bayesian reasoning and graphical models.

## 🔍 Key Features

- Generates synthetic medical data with logical dependencies  
- Constructs a directed Bayesian Network manually  
- Learns marginal and conditional probabilities from data  
- Predicts outcomes using learned probability tables  
- Visualizes the network structure using `networkx`  
- Validates model behavior against raw statistical patterns  

## 🚀 Getting Started

To get started, clone the repository, install the required packages, and run the notebook:

```bash
git clone https://github.com/your-username/Bayesian-Network-Medical-Risk-PGM.git
cd Bayesian-Network-Medical-Risk-PGM
pip install pandas numpy matplotlib networkx
jupyter notebook medical_pgm.ipynb


```
## 📊 Example Use Case
Estimate the probability of heart disease for a given patient profile:

```
evidence = {'Age': 'Old', 'Smoking': 'Yes', 'Exercise': 'No'}
model.predict_probability('Heart_Disease', 'Yes', evidence)
```

## 📘 Concepts Demonstrated
- Bayesian networks

- Conditional and marginal probability

- Directed acyclic graphs (DAGs)

- Probabilistic inference

- Model validation using raw data

## 📝 License
This project is open-source and available under the MIT License.

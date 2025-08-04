# 📘 Data Science Mini-Projects

This repository contains a curated collection of small, topic-focused exercises completed during my Data Science training.  
Each folder demonstrates hands-on experience with a specific algorithm, modeling concept, or implementation technique in machine learning, NLP, or statistics.

> 💡 These are not production-grade apps, but clear, focused implementations of important concepts.

---

## 📚 Topics Covered

| Folder | Topic | Description |
|--------|-------|-------------|
| `API_Model_Prediction/` | Flask API + Model | A small FastAPI-like app using Flask that loads a trained model (`DecisionTreeClassifier`) to predict student success. Includes input validation and `/predict` and `/health` endpoints. |
| `KNN_Marketing/` | KNN Classifier | Optimized a KNN model (k=1–20) on a marketing dataset with F1/ROC metrics, and analyzed performance by age and marital status using visualizations. |
| `L1L2_Regularization/` | Regularization & Comparison | Built synthetic balanced and unbalanced datasets and tested Logistic Regression with/without L1/L2 regularization. Compared it with Random Forests and visualized performance (AUC, PR). |
| `Markov_Simulation/` | Markov Chains | Simulated a fault-diagnosis process using transition probabilities. Visualized the chain with `networkx` and analyzed success rates, state visits, and step distributions. |
| `MonteCarlo_NLP/` | Monte Carlo | Multiple applications: MC dropout for text generation, estimating π, project risk simulation, and decision-making under uncertainty. Includes uncertainty propagation in sentiment analysis (VADER). |
| `Intent_Reasoning/` | Keyword-based Reasoning | Built a simple intent detection tool using keyword scoring logic. Supports multiple intents per sentence, with evaluation based on set similarity between predicted and true labels. |

---

## 🛠 Technologies Used

- **Python** (NumPy, pandas, scikit-learn, seaborn, matplotlib)
- **NLP**: Hugging Face Transformers, VADER
- **API**: Flask, joblib
- **Visualization**: Seaborn, NetworkX
- **Modeling**: Logistic Regression, KNN, Random Forest, Decision Trees
- **Simulation**: Monte Carlo, Markov Chains

---

## 🔍 How to Navigate

Each folder contains:

- `.py` script or `.ipynb` notebook with clear logic and outputs
- Comments and docstrings explaining the process
- Visual outputs for key steps (ROC, histograms, graphs)

---

## 🎓 Purpose

This repo is meant to:

- Show breadth of practical concepts I've practiced during my studies
- Serve as a starting point for deeper implementations
- Demonstrate clean and thoughtful code, even on small-scale tasks

---

## 📫 Contact

📍 Yuval Goldman  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/yuval-goldman-1a6920204/)  
📬 Feel free to reach out with feedback, suggestions or collaboration ideas!


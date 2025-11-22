# Reinforcement Learning in Machine Learning

This repository contains implementations of **Upper Confidence Bound (UCB)** and **Thompson Sampling**, two reinforcement learning algorithms designed to solve the **Multi-Armed Bandit Problem**.  
Both models are applied to the **Ads CTR Optimization Dataset** to determine which advertisement yields the best click-through rate.

---

## 📁 Project Structure

```bash
REINFORCEMENT LEARNING
│
├── .vscode/
│
├── Ads_CTR_Optimisation.csv
│
├── Upper Confidence Bound (UCB)
│ ├── upper_confidence_bound.ipynb
│ └── upper_confidence_bound.py
│
└── Thompson Sampling
├── thompson_sampling.ipynb
└── thompson_sampling.py
```


---

## 📊 Dataset

**Ads_CTR_Optimisation.csv** simulates user interactions with multiple ads by providing binary outcomes representing clicks (1) or no clicks (0).  
The task is to identify which ad performs best with minimal exploration cost.

---

## 🧠 Algorithms Used

| Algorithm | Purpose | Key Concept |
|-----------|---------|-------------|
| Upper Confidence Bound (UCB) | Balances exploration and exploitation using confidence intervals | Uses count of selections + average reward |
| Thompson Sampling | Probabilistic method for reward prediction and decision-making | Beta distribution for sampling best action |

---

## 🚀 Tools & Technologies

- Python  
- NumPy  
- Pandas  
- Matplotlib  

---

## 📈 Output Highlights

- Ad selection patterns over time  
- Comparative performance visualization  
- Optimized reward calculation for real decision systems  

---

## 🔗 Future Enhancements

- Add epsilon-greedy reinforcement strategy  
- Add reward comparison dashboard  
- Extend dataset for real-world CTR cases  

---

## 🧑‍💻 Author

Created as part of machine learning project development and reinforcement learning practice.

---

### ⭐ If this repository helps you, feel free to star it.

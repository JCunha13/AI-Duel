# ⚔️ AI Duel: Where Defense Learns from the Adversary

This project demonstrates a cutting-edge approach to **Cybersecurity Data Science**, simulating a continuous battle between a sophisticated attacker and an evolving defense mechanism.

## 📖 The Concept
Most security models are static; they fail when faced with new, unseen patterns. The **AI Duel** framework uses **Adversarial Machine Learning** to bridge this gap. 

### 🔴 The Red Team (Adversary)
- Uses **Markov Chains** and **NLP** to mimic human behavior.
- Camouflages malicious payloads (SQLi/XSS) within natural language to bypass entropy-based filters.

### 🔵 The Blue Team (Defense)
- **V1 (Static):** A traditional model that fails against mimicry attacks.
- **V2 (Evolutionary):** Uses **Semantic Tokenization** and an automated feedback loop to learn from the adversary's successful evasions.

## 📊 Key Results
- **Resilience:** The Evolutionary Defense (V2) recovered from a 15% detection rate to **99% accuracy** after adversarial retraining.
- **Robustness:** High recall on fraud detection, minimizing False Negatives (the costliest errors in security).

## 🛠️ Tech Stack
- **Python 3.10+**
- **Scikit-learn:** Random Forest & Isolation Forest.
- **Imbalanced-learn:** SMOTE for synthetic fraud data generation.
- **Matplotlib:** Advanced data visualization in "Cyber-Dark" mode.

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone [https://github.com/your-username/AI-Duel.git](https://github.com/your-username/AI-Duel.git)


# Intelligent Agent for Difficulty Level Estimation of Algebraic Questions

This repository contains code and resources for the paper:
**"Intelligent Single Agent Optimizer for Determining the Difficulty Level of an Algebraic Question"**

## 🧠 Overview

We present a reinforcement learning-based framework using the Multi-Armed Bandit (MAB) setup to estimate the difficulty levels of algebraic problems based on student performance. The agent leverages marks and time to compute a gain metric and selects questions accordingly.

## 📊 Dataset

You can access the publicly available dataset here:  
**[Performance Algebraic Questions Dataset – Kaggle](https://www.kaggle.com/datasets/jitdaz/performance-algebric-questions-data)**

Fields include:
- `ID`: Unique student identifier
- `Problem Class`: Classification of the question type
- `Problem ID`: Unique identifier for the question
- `milsec`: Time taken (in milliseconds)
- `marks`: Marks obtained (0 or 5)

## 🛠 Usage

### Installation
```bash
git clone https://github.com/yourusername/intelligent-difficulty-agent.git
cd intelligent-difficulty-agent
pip install -r requirements.txt
```

### Running the simulation
```bash
python src/main.py
```

## 📁 Project Structure

```
intelligent-difficulty-agent/
├── data/                 # Placeholder for dataset (or use Kaggle link)
├── src/                  # Source code
│   ├── main.py           # Main simulation logic
│   ├── preprocessing.py  # Data loading and preprocessing
│   ├── plotting.py       # Visualization scripts
│   └── utils.py          # Helper functions
├── LICENSE
├── README.md
├── requirements.txt
└── .gitignore
```

## 📜 License

This project is licensed under the MIT License.

## 📣 Citation

If you use this work, please cite:
```
@article{your2025agent,
  title={Intelligent Single Agent Optimizer for Determining the Difficulty Level of an Algebraic Question},
  author={Your Name et al.},
  journal={Under review},
  year={2025}
}
```

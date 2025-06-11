# Market-Basket-Analysis

This project focuses on mining association rules from transactional datasets using three popular algorithms: **Apriori**, **FP-Growth**, and **CLOSET**. The aim is to uncover hidden patterns, frequent itemsets, and meaningful associations between items in large datasets, which are essential techniques in market basket analysis and recommendation systems.

## 🧠 Algorithms Implemented

- **Apriori Algorithm**: A classic algorithm that uses a breadth-first search strategy and pruning to efficiently discover frequent itemsets.
- **FP-Growth (Frequent Pattern Growth)**: An advanced algorithm that constructs a compact FP-tree to mine frequent patterns without candidate generation.
- **CLOSET (Closed Itemset Mining)**: A depth-first approach to efficiently mine **closed frequent itemsets**, which are more compact and informative.

## 📊 Key Features

- Generation of frequent itemsets using all three algorithms.
- Extraction of strong association rules based on support and confidence thresholds.
- Comparative analysis of the algorithms based on performance and output.
- Clear visualization of itemsets and rules.
- Modular and extensible codebase suitable for integration with larger data mining pipelines.

## 🛠 Technologies Used

- Python
- `mlxtend` and custom implementation
- Jupyter Notebook for experimentation and demonstration


## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/shubhro2002/Market-Basket-Analysis.git
   cd Market-Basket-Analysis

2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
4. Run the Jupyter notebooks or Python scripts to start mining itemsets and generating rules

# mathematicaandstatistics
# Statistics and Linear Algebra Using Python

## 📌 Project Overview

This project demonstrates the implementation of:

* Linear Algebra operations using NumPy
* Probability concepts using Python, NumPy, and SciPy
* Descriptive Statistics using NumPy, Pandas, and Statistics libraries

The project is designed for beginners in Data Science and Machine Learning to understand mathematical and statistical concepts with Python programming.

---

# 🚀 Technologies Used

* Python
* NumPy
* Pandas
* SciPy
* Matplotlib
* Statistics Library

---

# 📂 Project Structure

```bash id="sbd4u5"
Statistics-LinearAlgebra-Project/
│
├── linear_algebra.py
├── probability_concepts.py
├── descriptive_statistics.py
├── requirements.txt
└── README.md
```

---

# 📘 Task 1 – Linear Algebra Implementation

## 📌 Objectives

Using NumPy:

* Perform vector addition
* Perform vector subtraction
* Calculate dot product
* Perform matrix addition
* Perform matrix multiplication
* Calculate determinant of matrix
* Find inverse of matrix
* Compute eigenvalues and eigenvectors

---

## 📊 Dataset

```python id="y1gdxu"
import numpy as np

vector_a = np.array([2, 4, 6])
vector_b = np.array([1, 3, 5])

matrix_a = np.array([
    [2, 1, 3],
    [1, 0, 2],
    [4, 1, 1]
])

matrix_b = np.array([
    [1, 2, 0],
    [3, 1, 4],
    [2, 5, 1]
])
```

---

## 🧠 Concepts Covered

* Vector Operations
* Matrix Operations
* Determinant
* Matrix Inverse
* Eigenvalues
* Eigenvectors

---

# 📘 Task 2 – Probability Concepts

## 📌 Objectives

Using Python / NumPy / SciPy:

* Calculate probability of successful sales
* Demonstrate conditional probability
* Apply Bayes’ theorem
* Simulate binomial distribution
* Generate normal distribution
* Generate uniform distribution

---

## 📊 Dataset

### Sales Probability Dataset

```python id="1qlcxy"
sales_success = [0.65, 0.35]
```

### Customer Segment Dataset

```python id="wlfddm"
customer_segments = ["Premium", "Regular"]

segment_purchase_probability = {
    "Premium": 0.80,
    "Regular": 0.50
}
```

### Bayes Theorem Dataset

```python id="xtsd9j"
P_A = 0.40
P_B = 0.62
P_B_given_A = 0.80
```

### Binomial Distribution Parameters

```python id="aq3k6z"
n_trials = 20
success_prob = 0.65
```

### Distribution Parameters

```python id="6t97gm"
normal_mean = 50
normal_std = 10

uniform_low = 0
uniform_high = 1
```

---

## 🧠 Concepts Covered

* Probability
* Conditional Probability
* Bayes’ Theorem
* Binomial Distribution
* Normal Distribution
* Uniform Distribution

---

# 📘 Task 3 – Descriptive Statistics

## 📌 Objectives

Using NumPy / Pandas / statistics library:

* Compute mean
* Compute median
* Compute mode
* Calculate range
* Calculate variance
* Calculate standard deviation
* Measure skewness
* Measure kurtosis
* Interpret dataset distribution

---

## 📊 Dataset

```python id="tmt2ga"
sales_data = [
    120, 135, 150, 145, 160,
    155, 170, 165, 180, 175,
    190, 200, 210, 195, 185,
    175, 165, 155, 145, 135
]
```

---

## 🧠 Concepts Covered

* Mean
* Median
* Mode
* Variance
* Standard Deviation
* Skewness
* Kurtosis
* Data Distribution Analysis

---

# 📈 Output Visualizations

The project generates:

* Binomial Distribution Graph
* Normal Distribution Histogram
* Uniform Distribution Histogram

---

# ▶️ How to Run the Project

## Step 1: Clone the Repository

```bash id="7f88yu"
git clone <your_repository_link>
```

---

## Step 2: Navigate to Project Folder

```bash id="lg4s8h"
cd Statistics-LinearAlgebra-Project
```

---

## Step 3: Install Required Libraries

```bash id="0pm4b4"
pip install -r requirements.txt
```

---

## Step 4: Run Python Files

### Run Linear Algebra Program

```bash id="7n4hh7"
python linear_algebra.py
```

### Run Probability Concepts Program

```bash id="e9qxlh"
python probability_concepts.py
```

### Run Descriptive Statistics Program

```bash id="7qz6e5"
python descriptive_statistics.py
```

---

# 📦 Requirements

Create a `requirements.txt` file and add:

```txt id="0f8qjf"
numpy
pandas
scipy
matplotlib
```

---

# 🎯 Learning Outcomes

After completing this project, you will understand:

* Linear Algebra operations using NumPy
* Probability concepts in Data Science
* Statistical analysis techniques
* Data visualization using Matplotlib
* Distribution analysis
* Practical Python implementation for Data Science

---

# 📌 Conclusion

This project provides hands-on implementation of mathematical and statistical concepts used in Data Science, Machine Learning, and Artificial Intelligence. It strengthens understanding of probability, linear algebra, and descriptive statistics using Python libraries.

---

# 👨‍💻 Author

Mohamed Liyakath Ali
B.Tech – Artificial Intelligence and Data Science
M.A.M College of Engineering

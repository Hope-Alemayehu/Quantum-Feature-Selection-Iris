## Quantum Probability Feature Selection (QPFS) on the Iris Dataset

This project demonstrates **Quantum Probability Feature Selection (QPFS)** applied to the **Iris dataset**, implemented in a **Jupyter Notebook**. The primary goal of this project is to explore **Quadratic Programming (QP)** concepts and their application in feature selection using quantum-inspired optimization.

---

### 🚀 Purpose

The purpose of this project is twofold:

1. **Learning Quadratic Programming**: Understanding the principles of QP and how it applies to optimization problems in machine learning.
2. **Applying QPFS**: Using QPFS to evaluate feature relevance and redundancy for feature selection, leveraging quantum-inspired methods.

---

### 📊 Dataset: Iris

The **Iris dataset** is a widely used dataset in machine learning and contains:

- **150 samples** of iris plants across three species: *Setosa*, *Versicolor*, and *Virginica*.
- **4 features**:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- **Target variable**: The species classification.

---

### 🛠️ Key Steps in the Notebook

1. **Data Loading and Preprocessing**:
   - Loaded the Iris dataset and split it into training and testing sets.
   - Standardized the features for consistent scaling.

2. **Calculating Feature Relevance (F)**:
   - Computed the relevance of each feature to the target variable using correlation.

3. **Calculating Feature Redundancy (Q)**:
   - Constructed a correlation matrix to evaluate feature redundancy.

4. **Encoding QPFS Objective Function**:
   - Formulated the optimization problem by combining relevance and redundancy.
   - Encoded the objective into a Hamiltonian representation.

5. **Quantum Optimization**:
   - Submitted the Hamiltonian to the Dirac-3 device using the QCi API.
   - Retrieved and analyzed the optimized solution.

---

### 📊 Results

The QPFS optimization identifies the most relevant and least redundant features from the Iris dataset. Results are stored in the `results/qpfs_solution.json` file, detailing the selected features and the corresponding optimization energy.

---

### 🔍 Key Insights

- Quadratic Programming simplifies the balance between relevance and redundancy in feature selection.
- Quantum-inspired optimization using Dirac-3 highlights the potential for solving high-dimensional problems efficiently.
- The project serves as a foundational step for extending QPFS to more complex datasets like Parkinson's.

---

### 🤝 Contributing

Contributions are welcome! If you have ideas to enhance the project or extend it to other datasets, feel free to open issues or submit pull requests.

---

### 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

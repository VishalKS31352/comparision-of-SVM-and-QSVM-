# SVM vs QSVM on Air Pollution Classification

This project compares classical SVM vs Quantum SVM (QSVM) using an air pollution dataset. The dataset contains **4 mean feature values** (PM2.5, PM10, NO2, SO2) and each sample is labelled as **Good / Moderate / Bad**.

## Objective

Evaluate how a classical ML decision boundary (SVM) differs from a quantum kernel based boundary (QSVM) when features are low-dimensional.

## Features Used

- CO Mean
- SO2 Mean
- NO2 Mean
- O3 Mean

## Labels

- Good
- Moderate
- Bad

## Tech

| Component | Used |
|----------|------|
| Classical | Scikit-Learn SVM |
| Quantum   | Qiskit (QuantumKernel)|
| Language  | Python |
| Notebook  | Jupyter |

## Steps

1. Import dataset
2. Preprocess + extract 4 mean pollutant columns
3. Encode labels into numeric format
4. Train Classical SVM as baseline
5. Train QSVM using Quantum Kernel
6. Compare:
   - Accuracy
   - F1 Score
   - Confusion Matrix

## Why This Matters

Quantum ML is expected to show advantages in low-dimension non-linear structures.  
Air pollution features (4 means) is a real-world low-feature scenario — making this a good early test to understand how QSVM behaves vs SVM.

## Folder Structure (example)


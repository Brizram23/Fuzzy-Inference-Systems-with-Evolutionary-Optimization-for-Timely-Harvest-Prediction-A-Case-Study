# Fuzzy-Inference-Systems-with-Evolutionary-Optimization-for-Timely-Harvest-Prediction-A-Case-Study
Fuzzy Inference Systems with Evolutionary Optimization for Timely Harvest Prediction: A Case Study
# Stevia Harvest Prediction using Fuzzy Inference System and Genetic Algorithm

This project implements a fuzzy inference system (FIS) optimized with a genetic algorithm (GA) to predict the optimal harvest time for *Stevia rebaudiana*. The model estimates the °Brix value (sweetness) of the crop based on key meteorological variables.

## 📂 Files Included

- `SID (1).ipynb`: Main Jupyter Notebook containing all code for:
  - Data loading and preprocessing
  - FIS design and optimization
  - Evaluation and metrics
  - Visualization of results

- `POWER_Quarterly_Aggregated_with_Top5_Clusters_Brix (3).csv`: Dataset containing quarterly aggregated meteorological data and corresponding °Brix values.

## 📊 Dataset Description

The dataset includes the following columns:
- `ALLSKY_KT`: Clear sky index (solar radiation)
- `QV2M`: Specific humidity at 2 meters
- `T2MDEW`: Dew point temperature at 2 meters
- `PRECTOTCORR_SUM`: Total accumulated precipitation
- `PRECTOTCORR`: Average daily precipitation
- `Grados Brix`: Target variable indicating sweetness level

## ⚙️ Model Overview

- **Model type**: Mamdani-type Fuzzy Inference System
- **Optimization**: Genetic Algorithm (population-based search)
- **Membership Functions**: Triangular, Trapezoidal, and Gaussian
- **Evaluation metrics**: Accuracy, Precision, Recall, F1-Score, Mean Squared Error

## ▶️ How to Run

1. Open `SID (1).ipynb` in Jupyter Notebook or Google Colab.
2. Upload the CSV dataset when prompted or ensure it's in the same directory.
3. Run the notebook cells sequentially.
4. Results will display performance metrics and visualizations.

## 📌 Notes

- This implementation includes comparisons with baseline models (MLP, non-optimized FIS).
- The system is fully interpretable and designed for decision support in precision agriculture.

## 📜 License

For academic and non-commercial use only. Please cite appropriately if used in publications.

## 🙏 Acknowledgments

This project was supported by:
- Secretaría de Ciencia, Humanidades, Tecnología e Innovación (SECIHTI)
- Tecnológico Nacional de México, Campus Colima
- Rancho Tajeli, for providing agronomic field data.

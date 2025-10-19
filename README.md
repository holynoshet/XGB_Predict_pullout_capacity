# Catboost Model for Predicting Anchor Pull-out Capacity

This repository contains the graphical user interface (GUI) tool for the research paper: *"A Physics-Informed, Interpretable Machine Learning Framework to Calibrate the Pull-out Capacity of Anchors in SFRC"*.

## 🚀 Quick Start

1.  Navigate to the [**Releases**](https://github.com/holy-not-shit/Catboost_Predict_pullout_capacity/releases) page of this repository.
2.  Download the `predict_pullout_capacity.exe` file from the latest release.
3.  Run the application. No other downloads or installations are required.

### Applicability and Limitations

⚠️ **Please note**: The underlying CatBoost model was trained on a specific dataset. The predictions are most reliable within the following parameter ranges:

*   **Fiber volume fraction (`V_f`)**: 0.38% – 1.60%
*   **Fiber aspect ratio (`l_f/d_f`)**: 19.63 – 65.20
*   **Concrete compressive strength (`f_c`)**: 30.70 – 65.30 MPa
*   **Member thickness (`h`)**: 70 – 440 mm
*   **Embedment depth (`h_ef`)**: 25 – 220 mm
*   **Anchor diameter (`d_a`)**: 8 – 36 mm

*Using the tool for predictions with parameters outside of these ranges (extrapolation) should be done with caution and ideally validated with experimental data.*
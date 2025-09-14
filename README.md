# Space Debris vs Satellite Classification using Machine Learning

This repository contains the implementation and dataset for the research paper:
**"Classification of Space Debris and Satellites using TLE Data and Machine Learning Models"**,  
submitted to the All India Technical Conference 2025.

---

## Project Overview
- Problem: Increasing space debris poses risks to satellites and space missions.
- Solution: Machine Learning models trained on **Two-Line Element (TLE) data** to classify objects as *satellite* or *debris*.
- Approach: Feature extraction from TLE parameters → Preprocessing → ML Classification → Evaluation.

---

## Tech Stack
- **Python**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**
- Dataset: [CelesTrak TLE Data](https://www.celestrak.com/)


## Methodology
1. **Dataset Collection** – TLE parameters (inclination, eccentricity, mean motion, etc.)
2. **Preprocessing** – Cleaning, normalization, labeling.
3. **Model Training** – Random Forest, SVM, and baseline models.
4. **Evaluation** – Accuracy, Precision, Recall, F1-score, Confusion Matrix.

---

## Results
- Random Forest achieved the highest accuracy (~95%).
- Feature importance analysis showed inclination, eccentricity, and mean motion are critical features.
- Visualization:
  - Confusion Matrix (Debris vs Satellite)
  - Feature Importance Graph

---

## 🖼Sample Output

Confusion Matrix :
<img width="815" height="683" alt="image" src="https://github.com/user-attachments/assets/fe3d1450-2cc6-46ea-9bb4-3ad874ff3760" />
Feature Importance : 
<img width="834" height="793" alt="image" src="https://github.com/user-attachments/assets/5dcdf2a8-b1be-4f2e-bf92-a9c2fcb480c7" />


## Code Availability
The complete code and dataset are available in this repository.  
You can run the notebook directly in **Google Colab**:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/13iTZWhPVeJsDdRiJGYCONtQYVeDlCsr0?usp=sharing)


## Acknowledgement
Special thanks to **CelesTrak** for TLE data and the open-source Python community.

# Prediction Animal Disease

## Project description
This project develops a machine learning system for predicting animal diseases using clinical symptoms, vital signs, and health indicators across multiple species. The system supports veterinary diagnostics by analyzing patterns in multispecies clinical records.

## Files
- `prediction_animal_disease.ipynb` — Python code (data cleaning, EDA, feature engineering, model training)
- `prediction_animal_disease.presentation.pdf` — presentation slides
- `prediction_animal_disease.report.pdf` — full project report
- `multispecies_dataset.csv` — raw data (Multispecies Diagnostic Records)

## Dataset
- **Size**: 14,976 animals
- **Species**: 32 animal types (Lion, Tiger, Elephant, Penguin, etc.)
- **Features**: 24 columns (age, weight, temperature, heart rate, symptoms, etc.)
- **Target**: 7 disease classes

## Key findings from EDA
- Sick animals have higher body temperature (2.4°C hotter on average)
- Healthy animals have Health Score 8-10, sick animals score lower
- Overlapping symptoms make exact disease prediction challenging

## Models compared
- Logistic Regression
- Random Forest
- XGBoost/Gradient Boost

## Technologies
- Python / Pandas / NumPy
- Scikit-learn (Logistic Regression, Random Forest)
- XGBoost
- Matplotlib / Seaborn (visualizations)
- Jupyter Notebook
- Overleaf — for report and presentation formatting (LaTeX)

## Interactive prediction
The system includes a real-time disease prediction function for veterinary diagnostic support.

# Parkinson's Disease Detection using XGBoost

Dieses Projekt nutzt Machine Learning, um die Parkinson-Krankheit bei Patienten anhand von medizinischen Sprachaufzeichnungen frühzeitig zu erkennen. Dabei kommt der **XGBoost-Algorithmus** (Extreme Gradient Boosting) zum Einsatz, der für seine hohe Genauigkeit bei tabellarischen Daten bekannt ist.

## 📌 Projektübersicht
Parkinson ist eine fortschreitende Erkrankung des Nervensystems, die die Bewegung beeinflusst. Frühe Symptome können sich in der Stimme zeigen. Dieses Modell analysiert verschiedene akustische Parameter (wie Jitter, Shimmer und Frequenzmessungen), um zwischen gesunden Personen und Parkinson-Patienten zu unterscheiden.

## 📊 Datensatz
Der verwendete Datensatz stammt aus dem **UCI Machine Learning Repository**.
- **Features:** 22 verschiedene akustische Merkmale der Stimme.
- **Zielvariable (`status`):** 1 für Parkinson-Patienten, 0 für gesunde Probanden.

## 🛠 Tech Stack
- **Sprache:** Python 3.x
- **Libraries:** - `xgboost` (Modellierung)
  - `scikit-learn` (Preprocessing & Evaluierung)
  - `pandas` & `numpy` (Datenverarbeitung)
  - `matplotlib` & `seaborn` (Visualisierung)

## 📂 Projektstruktur
```text
├── data/               # Enthält den Parkinson-Datensatz (CSV)
├── notebooks/          # Jupyter Notebooks für EDA und Experimente
├── models/             # Gespeicherte, trainierte Modelle
├── src/                # Finaler Python-Quellcode
├── README.md           # Projektdokumentation
├── requirements.txt    # Benötigte Python-Bibliotheken
└── .gitignore          # Auszuschließende Dateien für Git

# Diabétesz Kockázat Előrejelzés

Gépi tanulási projekt a diabétesz kockázat előrejelzésére sklearn adatkészlet használatával.

## 📋 Projekt Leírás

Ez a projekt két bináris osztályozási forgatókönyvet valósít meg:
- **1. forgatókönyv**: Küszöbérték 150 - korai felismerés
- **2. forgatókönyv**: Küszöbérték 250 - súlyos esetek azonosítása

## 📁 Fájlok

- `diabetes_risk_prediction.ipynb` - Teljes elemzés és modellek
- `diabetes_data.csv` - Exportált adatkészlet
- `hw_risk_prediction.md` - Feladat leírás (angol)
- `hw_risk_prediction.hu.md` - Feladat leírás (magyar)
- `hw_risk_prediction.pdf` - Feladat dokumentáció

## 🚀 Használat

1. Virtuális környezet aktiválása:
```bash
.venv\Scripts\activate
```

2. Notebook megnyitása és futtatása:
```bash
jupyter notebook diabetes_risk_prediction.ipynb
```

## 📊 Eredmények

- **Legjobb modell (1. forgatókönyv)**: Logisztikus regresszió (F1: 0.775)
- **Legjobb modell (2. forgatókönyv)**: Logisztikus regresszió (F1: 0.636)

## 🛠️ Technológiák

- Python 3.12
- scikit-learn
- pandas
- matplotlib
- seaborn
- numpy

## 📅 Dátum

Létrehozva: 2026. február 4.

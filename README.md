# Modelowanie Ryzyka Kredytowego

Projekt analizuje ryzyko kredytowe na podstawie publicznego datasetu z Kaggle. Celem jest klasyfikacja binarna — przewidywanie defaultu.

## Co zawiera notebook (`MRK_SMOTE.ipynb`)

- Eksploracja i wizualizacja danych (rozkłady, korelacje, wartości brakujące)
- Balansowanie klas za pomocą **SMOTE** (oversampling mniejszości)
- Trenowanie i porównanie modeli:
  - Regresja Logistyczna
  - Drzewo Decyzyjne
  - Random Forest
  - XGBoost
- Ocena modeli: Accuracy, Precision, Recall, F1, ROC-AUC, AUPRC
- Analiza ważności cech (**SHAP**)

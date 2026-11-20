# wa-la-yahimk-nids
Hybrid, interpretable network intrusion detection: RF + XGBoost weighted voting, two-phase feature selection, SMOTE/ADASYN/cost-sensitive learning, SHAP explanations, and LSTM/Bi-LSTM attack-frequency forecasting on CICIDS2017, UNSW-NB15 and CICDDoS2019.
# Wa la Yahimk – Hybrid and Interpretable Network Intrusion Detection

Graduation project. A framework for multi-class intrusion detection using
Random Forest + XGBoost (weighted voting), two-phase feature selection,
SMOTE / ADASYN / cost-sensitive learning, SHAP explanations, and a separate
LSTM / Bi-LSTM component for attack-frequency forecasting.

## Datasets 
- CICIDS2017: https://www.unb.ca/cic/datasets/ids-2017.html
- UNSW-NB15: https://research.unsw.edu.au/projects/unsw-nb15-dataset
- CICDDoS2019: https://www.unb.ca/cic/datasets/ddos-2019.html
  (cleaned Parquet version: https://www.kaggle.com/datasets/dhoogla/cicddos2019)

## How to run
1. Open `Wa_la_Yahimk_Colab_v4_5seeds.ipynb` in Google Colab.
2. Upload the datasets (or use Google Drive) and run the cells in order.
3. Results (tables, figures, Excel) are exported to the outputs folder.

## Experimental settings
Five seeds (42–46), paired t-test / Wilcoxon with Holm adjustment,
variant CICDDoS2019-merged (paired labels merged).

## Team
- [Student names]

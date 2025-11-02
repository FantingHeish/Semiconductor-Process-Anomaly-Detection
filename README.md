## Semiconductor-Process-Anomaly-Detection

### 專案簡介
使用 XGBoost、Isolation Forest、Autoencoder、VAE 等模型偵測半導體製程資料中的潛在異常樣本與感測器異常行為，協助提升製程良率與穩定性。本專案以 UCI SECOM 半導體製程資料集為基礎，建立多種監督式與非監督式異常偵測模型，用於辨識製程中可能造成良率下降的異常訊號來源。

### 技術架構
- **開發框架：** Scikit-learn、TensorFlow  
- **模型：** XGBoost、Isolation Forest、Autoencoder、VAE  
- **評估指標：** ROC-AUC、PR-AUC、Accuracy

### 專案檔案說明
- `Semiconductor_Anomaly_Detection.ipynb`：主要模型訓練與分析流程  
- `requirements.txt`：環境套件清單  

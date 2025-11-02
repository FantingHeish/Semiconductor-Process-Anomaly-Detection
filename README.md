## Semiconductor-Process-Anomaly-Detection(半導體製程異常偵測)

使用 XGBoost、Isolation Forest、Autoencoder、VAE 等模型偵測半導體製程資料中的潛在異常樣本與感測器異常行為，協助提升製程良率與穩定性。

---

### 專案簡介
本專案以 UCI SECOM 半導體製程資料集為基礎，建立多種監督式與非監督式異常偵測模型，  
用於辨識製程中可能造成良率下降的異常訊號來源。比較多種模型效能後，  
Variational Autoencoder (VAE) 在準確率與 AUC 上皆表現最佳。

---

### 技術架構
- **開發框架：** Scikit-learn、TensorFlow  
- **模型：** XGBoost、Isolation Forest、Autoencoder、VAE  
- **評估指標：** ROC-AUC、PR-AUC、Accuracy

---

### 模型效能
| 模型 | ROC-AUC | PR-AUC | Accuracy |
|------|----------|--------|-----------|
| XGBoost | 0.69 | 0.18 | 90.1% |
| Isolation Forest | 0.71 | 0.19 | 91.2% |
| Autoencoder | 0.72 | 0.20 | 92.3% |
| **VAE** | **0.73** | **0.20** | **92.7%** |

---

### 專案檔案說明
- `Semiconductor_Anomaly_Detection.ipynb`：主要模型訓練與分析流程  
- `requirements.txt`：環境套件清單  
- `model_results.png`：結果視覺化圖表  

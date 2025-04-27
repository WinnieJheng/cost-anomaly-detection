# Cost Anomaly Detection System using Autoencoder

This project is an AI-powered solution for automated anomaly detection in utility expenses (water, electricity, internet) across multiple construction sites. By leveraging an unsupervised learning approach with Autoencoder, the system identifies unusual cost patterns without the need for predefined thresholds.

## 🚀 Project Overview
- **Objective**: Detect abnormal utility expenses to support financial control and reduce manual auditing efforts.
- **Data**: Simulated dataset covering 5 construction sites, 3 types of expenses, over 12 months.
- **Output**: Automated generation of Excel reports highlighting anomalies.

## 🛠️ Technologies Used
- Python
- TensorFlow (Autoencoder Neural Network)
- Scikit-learn
- Pandas

## 📂 Features
- Unsupervised anomaly detection based on reconstruction error.
- Dynamic threshold setting (95th percentile of MSE) for each site and expense type.
- Automated processing of multi-site, multi-expense data.
- Generates Excel reports in the same directory:
  - `Cost_Anomaly_Full_Report.xlsx` : Complete data with anomaly flags (True/False).
  - `Cost_Anomaly_Only_Report.xlsx` : Filtered report showing only detected anomalies.
  - `Anomaly_Summary_Report.xlsx` : Summary of anomaly counts and amounts per site and expense type.

## 📈 Example Results
- **Total records processed**: 180
- **Anomalies detected**: 15
- Example: Site A001, Water Bill in March increased by 200% compared to the average.

## 💡 How to Use
1. Place your raw data file in the same directory as the notebook.
2. Run `Cost_Anomaly_Detection_System.ipynb`.
3. The system will automatically generate Excel reports in the same directory.

## 🎯 Benefits
- Reduces manual inspection time.
- Enhances financial transparency and risk management.
- Easily adaptable to different types of cost data.

---

Feel free to customize the dataset and thresholds according to your business needs!

# 費用異常偵測系統｜Autoencoder 應用

本專案為一套 AI 驅動的自動化異常偵測解決方案，針對多個工地的水費、電費、網路費進行費用異常分析。透過無監督式學習的 Autoencoder 模型，無需事先設定固定門檻，即可自動辨識異常費用模式，協助企業強化財務控管與降低人工稽核成本。

## 🚀 專案概述
- **目標**：偵測工地日常營運中的異常水電網費支出，提前發現潛在財務風險。
- **數據來源**：模擬數據，涵蓋 5 個工地、3 種費用類型，橫跨 12 個月份。
- **輸出成果**：自動生成標記異常的 Excel 報告，提供管理層快速檢視。

## 🛠️ 使用技術
- Python
- TensorFlow（Autoencoder 神經網路）
- Scikit-learn
- Pandas

## 📂 功能特色
- 基於重建誤差的無監督異常偵測機制。
- 每個工地與費用類型動態設定閾值（MSE 第 95 百分位）。
- 支援多工地、多費用類型的批次自動化處理。
- 生成以下報告（儲存於同一目錄）：
  - `費用異常偵測報告.xlsx` ：完整數據（含正常與異常標記）。
  - `異常數據報告.xlsx` ：僅顯示判斷為異常的數據。
  - `異常摘要報告.xlsx` ：依工地與費用類型彙總異常次數與金額。

## 📈 成果範例
- **總處理筆數**：180 筆
- **偵測異常筆數**：15 筆
- 範例：工地 A001 於 3 月水費支出較平均增加 200%，被判定為異常。

## 💡 使用方式
1. 將原始數據檔放置於程式同一目錄下。
2. 執行 `Cost_Anomaly_Detection_System.ipynb`。
3. 系統將自動產出報告於同目錄下。

## 🎯 專案效益
- 大幅減少人工逐筆檢查時間。
- 提升財務透明度與異常風險管理能力。
- 可依業務需求靈活調整數據與偵測門檻。

---

歡迎依據不同場景自行調整數據來源與異常判定邏輯，打造專屬的智能費用監控系統！


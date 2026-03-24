## 專案一：銷售量分析與預測 (Sales Volume Analysis and Prediction)
1. 專案簡介
本專案旨在分析超商的銷售數據，透過歷史數據探索銷售趨勢，並建立時間序列模型預測未來的銷售量，協助企業進行庫存管理與營運策略優化。

2. 資料來源與工具
資料來源：Kaggle 數據集（超商定期銷售數據）。
分析工具：
Power BI：進行視覺化探索，提供下拉式選單篩選不同年度、產品分類、地區及州別。
Python (Pandas, Statsmodels, Matplotlib)：進行數據清洗、統計分析與建模。
3. 實作重點
數據預處理：日期格式轉換（Order Date）、缺失值處理、數據類型最佳化。
視覺化分析：透過 Power BI 儀表板，即時掌握不同維度（如 Category, Sub-Category, Region）的銷售表現。
時間序列建模：
平穩性檢定：使用 Augmented Dickey-Fuller (ADF) Test 確認資料是否平穩。
特徵探索：繪製 ACF 與 PACF 圖形，判斷模型參數。
預測模型：建立 ARIMA 模型（如 ARIMA(12, 1, 12)），對未來銷售趨勢進行預測。

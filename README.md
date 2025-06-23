# 論文補充資料: 從股市泡沫到個股韌性：指標分析之實證研究
# From Stock Market Bubbles to Individual Stock Resilience: An Empirical Study Based on Indicator Identification

本儲存庫收錄論文《從股市泡沫到個股韌性：指標分析之實證研究 》之線上補充資料，包含圖表、表格與原始分析結果，依內容分為四大類資料夾，說明如下：

This repository contains the supplementary materials for the paper *From Stock Market Bubbles to Individual Stock Resilience: An Empirical Study Based on Indicator Identification*. The repository includes figures, tables, and raw analysis results, organized into four folders as follows:

---

## 📁  個股韌性圖表（Individual Resilience Charts）

為進一步觀察個股韌性指標與股價之間的互動關係，本文選取台灣目前市值前五大公司（台積電、鴻海、聯發科、富邦金、廣達），繪製其四個韌性指標（DUVOL、NCSKEW、Vulnerability、Resilience）與個股股價的趨勢圖（共 20 張圖）。

To explore the interaction between resilience indicators and stock prices, we selected Taiwan's top five companies by market cap (TSMC, Hon Hai, MediaTek, Fubon Financial, and Quanta), and plotted the trends of four indicators against each stock's price (20 charts total).

- x 軸：時間（月）    x-axis: time (monthly)
- y 軸：韌性指標數值與加權指數點數（右軸）    y-axis: indicator value & market index

指標值視覺化處理方式如下：  
The visualization treatment of indicators:

- **Vulnerability、Resilience 指標**：值 > 0.5 設為 1，值 < 0.5 設為 0  
 (Probability-type: 1 if > 0.5, 0 otherwise)
- **DUVOL、NCSKEW 指標**：正數設為 1，負數設為 0  
 (Signed-type: 1 if positive, 0 if negative)
- 結果以陰影標示區間，輔助觀察指標與股價間的關聯  
 Shaded areas represent periods where indicator equals 1

📂 資料夾名稱 | Folder: `個股韌性圖表（Individual Resilience Charts）`

---

## 📁 泡沫狀態資料表（Bubble Status Tables）

本資料表整理四種泡沫辨識方法下的市場泡沫狀態（以 0/1 記錄）：

This folder contains bubble status (0/1) across four detection methods:

1. **GSADF（95% 臨界值）** GSADF test using 95% Monte Carlo critical value  
2. **GSADF（90% 臨界值）** GSADF test using 90% Monte Carlo critical value  
3. **本益比法**        Price-to-Earnings ratio exceeding historical mean + 2 std dev  
4. **實際事件法**       Manually defined based on historical financial crises

📂 資料夾名稱 | Folder: `泡沫狀態資料表 (bubble_detection_tables)`

---

## 📁 動態投資與0050績效比較圖 (Performance Chart:  0050 vs. Dynamic Strategy)

比較兩種策略的績效：

Comparison of two investment strategies:

- **策略一**：被動持有0050
 Strategy 1: Passive holding 0050 ETF  
- **策略二**：依泡沫判斷＋韌性選股之動態配置  
 Strategy 2: Dynamic allocation using bubble signals and resilience sorting

圖中標記泡沫期間轉換點與報酬路徑。  
The figures display switching points and cumulative returns under both strategies.

📂 資料夾名稱 | Folder: `動態投資與0050績效比較圖 (Dynamic_vs_0050_performance_charts)`


---

## 📁 動態投資與0050累積報酬比較表( Performance Tables: 0050 vs. Dynamic Strategy)

本資料夾收錄以「元大臺灣50指數（0050）」為基準，與各種泡沫辨識法與韌性指標所構成之「動態策略」間的累積報酬比較資料。每份 Excel 表格皆呈現：

- 不同泡沫檢定法（如本益比法、實際事件法）
- 不同韌性指標（如 DUVOL、NCSKEW、Resilience、Vulnerability）
- 動態策略 vs. 0050 的報酬路徑與差異

This folder contains cumulative return comparison tables between the 0050 ETF (Yuanta Taiwan Top 50) and dynamic investment strategies built on:

- Various bubble detection methods (e.g., P/E ratio, real-world events)
- Four resilience indicators (DUVOL, NCSKEW, Resilience, Vulnerability)
- Each Excel file presents the cumulative performance differences between the 0050 ETF and the corresponding dynamic strategy.

📂 資料夾名稱 | Folder: `動態投資與0050累積報酬比較表 / dynamic_vs_0050_returns_tables`


---
## 📁 動態投資與加權指數績效比較圖 (Performance Chart: TWII  vs. Dynamic Strategy)

比較兩種策略的績效：

Comparison of two investment strategies:

- **策略一**：被動持有加權指數
 Strategy 1: Passive holding of the market index 
- **策略二**：依泡沫判斷＋韌性選股之動態配置  
 Strategy 2: Dynamic allocation using bubble signals and resilience sorting

圖中標記泡沫期間轉換點與報酬路徑。  
The figures display switching points and cumulative returns under both strategies.

📂 資料夾名稱 | Folder: `動態投資與加權指數績效比較圖 (Dynamic_vs_twii_performance_charts)`


---

## 📁 動態投資與加權指數累積報酬比較表  (Performance Tables: TWII vs. Dynamic Strategies)

本資料夾收錄以「加權指數（TWII）」為基準，與各種泡沫辨識法與韌性指標所構成之「動態策略」間的累積報酬比較資料。每份 Excel 表格皆呈現：

- 不同泡沫檢定法（如本益比法、實際事件法）
- 不同韌性指標（如 DUVOL、NCSKEW、Resilience、Vulnerability）
- 動態策略 vs. 加權指數的報酬路徑與差異

This folder provides cumulative return comparison tables between the Taiwan Weighted Index (TWII) and multiple dynamic strategies constructed using:

- Various bubble detection methods (e.g., P/E ratio, historical crisis events)
- Four resilience indicators (DUVOL, NCSKEW, Resilience, Vulnerability)
- Each Excel file shows cumulative performance comparison between the TWII and the dynamic strategy.

📂 資料夾名稱 | Folder: `動態投資與加權指數累積報酬比較表 (Dynamic_vs_twii_returns_tables)`

---




## 📌 引用方式 | Citation

若您引用或參考本補充資料，請標註以下網址：  
If you reference or use this repository, please cite the following link:





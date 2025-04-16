# 📊 ETF 報酬波動與追蹤誤差分析專案

這是一個基礎金融資料分析專案，透過 Python 與 yfinance 套件，下載 VT 與 VTI 兩支美國 ETF 的歷史股價，觀察其每日報酬率，並找出波動最大的時間點，作為追蹤誤差研究的初步探索。

---

## 🔍 專案目的

- 熟悉金融資料的取得與清洗
- 計算報酬率與視覺化走勢
- 找出波動劇烈的市場時刻
- 作為後續碩士論文研究「Tracking Error」的實作基礎

---

## 📂 專案內容

| 分析項目 | 說明 |
|----------|------|
| ETF 選擇 | Vanguard Total World Stock ETF (VT)、Vanguard Total Stock Market ETF (VTI) |
| 資料來源 | Yahoo Finance (透過 `yfinance` 套件擷取) |
| 計算指標 | 日報酬率、報酬變動排序、震盪最大 Top 10 日 |
| 視覺化 | 使用 matplotlib 畫出收盤價走勢與報酬率走勢圖 |

---

## 🧪 使用技術

- `Python`
- `pandas`
- `matplotlib`
- `yfinance`
- `Google Colab`（或 Jupyter Notebook）

---

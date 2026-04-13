# 投資組合再平衡助理

**MFT105 Python 及其在金融中的應用** 期末專案  
風險平價再平衡決策支援工具（含穩健性分析 + Streamlit UI）

## 檔案說明
- Portfolio_Rebalance_Assistant.ipynb → 主程式碼（完整 pipeline）
- app.py → Streamlit 互動式 Dashboard（加分用）
- requirements.txt → 環境需求
- 報告 PDF → 短報告

## 安裝與執行
pip install -r requirements.txt
streamlit run app.py   # 或直接開啟 Notebook

## 執行順序
1. Notebook Cell 1-7（資料下載 → 再平衡建議）
2. （選用）app.py 啟動互動介面

## 預期輸出
見報告第 4 節截圖（權重表格、買賣建議、回測結果、圖表）

資料來源：Yahoo Finance（公開）
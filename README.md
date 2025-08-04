# 0050ETF報酬與風險分析專案

本專案使用 Python 與 yfinance 抓取台灣 0050 ETF 的歷史股價資料，計算並視覺化以下風險報酬指標：

## 分析內容

- 日報酬率與累積報酬率
- 年化報酬率
- 年化波動率
- Sharpe Ratio
- Value at Risk (VaR 5%)
- 最大回撤（Max Drawdown）

## 使用工具

- Python
- Jupyter Notebook
- yfinance
- pandas、numpy、matplotlib

## 專案結果摘要

| 年化報酬率 | 年化波動率 | Sharpe Ratio | VaR(5%) | 最大回撤 |
|------------|------------|---------------|--------|------------|
| 18.21%     | 21.89%     | 0.79          | -1.995% | -34.86%    |

## 專案檔案說明

- `01_etf_return_analysis.ipynb`：主程式，含完整分析流程
- `README.md`：專案介紹（您現在正在看）

## 結論與觀察

0050 ETF 在近年呈現穩定上升趨勢，風險報酬表現中等，最大回撤約為 -34.86%，Sharpe Ratio 為 0.79，投資人仍需留意極端下跌風險。

## 資料來源

- [Yahoo Finance - 0050.TW](https://finance.yahoo.com/quote/0050.TW/)

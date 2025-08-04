# 0050 ETF 報酬與風險分析
本專案使用 Python 對台灣元大 0050 ETF 進行歷史報酬率與風險分析，並運用金融指標（年化報酬、波動率、Sharpe Ratio、VaR、最大回撤）評估其風險與報酬特性。

## 分析項目
- 資料來源：yfinance 擷取Yahoo Finance台灣0050ETF（0050.TW）
- 分析項目：
  - 每日報酬率與累積報酬率計算與視覺化
  - 年化報酬率與年化波動率
  - Sharpe Ratio（風險調整報酬）
  - Value at Risk (VaR) 風險衡量
  - 最大回撤（Max Drawdown）分析與視覺化

## 核心成果
| 指標         | 數值     |
|-------------|----------|
| 年化報酬率    | 18.21%   |
| 年化波動率    | 21.89%   |
| Sharpe Ratio| 0.79     |
| VaR(5%)     | -1.995%  |
| 最大回撤     | -34.86%  |

## 使用工具
- Python
- Jupyter Notebook
- 套件：yfinance, numpy, pandas, matplotlib



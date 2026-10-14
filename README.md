# Python 與金融資料分析

銘傳大學財務金融學系 115 學年度第 1 學期課程講義與資料。

網站：https://chadhsu226.github.io/python-finance/

在 Colab 讀取資料：

```python
DATA_URL = "https://chadhsu226.github.io/python-finance/data/"
df = pd.read_csv(DATA_URL + "2330.csv", parse_dates=["Date"])
```

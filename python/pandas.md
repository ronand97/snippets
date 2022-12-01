
# set output width
https://stackoverflow.com/a/11711637

Update: Pandas 0.23.4 onwards

Pandas autodetects the size of your terminal window if you set

`pd.options.display.width = 0`

Older versions:
```python
import pandas as pd
pd.set_option('display.max_rows', 500)
pd.set_option('display.max_columns', 500)
pd.set_option('display.width', 1000)
```
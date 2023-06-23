# Loading the data
The following code can be used to import the CSV file of the white wines:

```python
import pandas as pd

data = pd.read_csv('https://github.com/AdrianRakk/amazon-reviews/raw/main/original/winequality-white.csv',
                   sep=';')
```

Data source: https://archive.ics.uci.edu/dataset/186/wine+quality

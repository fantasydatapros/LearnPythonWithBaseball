This section uses one CSV file. This data originates from [Fantasy Pros](https://www.fantasypros.com/mlb/rankings/overall.php#).

To use a csv use the `read_csv` method from pandas.
```python
import pandas as pd
```

In this section we use Fantasy Baseball 2022 Draft Rankings.
```python
salaries = pd.read_csv('https://raw.githubusercontent.com/fantasydatapros/LearnPythonWithBaseball/main/2021/08-Analyzing%20MLB%20Salary%20Data/Salaries.csv')
```

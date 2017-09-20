
My first attempt to do data analysis with python.

I am using the [Bike Sharing Dataset Data Set](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)

## Development Environment

```
docker run -d -p 8888:8888 jupyter/datascience-notebook start-notebook.sh --NotebookApp.token=''
```

## Data Import

```python
import pandas as pd

day_df = pd.read_csv("day.csv")
hour_df = pd.read_csv("hour.csv")
```

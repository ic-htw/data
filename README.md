# Data
Data files of different kinds to be used in my lectures

# Turn csv to parquet

```python
from edurel.utils.misc import csv_to_parquet

csv_to_parquet(
    in_path="/.../csv",
    fn="*",
    spec="header=true",
    out_path="/.../parquet",
    verbose=True
)
```

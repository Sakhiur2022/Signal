# Original SAKERNAS 2023 microdata (never modify)

## Infos

This dataset is uploaded on hugging face.
Code to download the dataset:

```python
import pandas as pd

url = "https://huggingface.co/datasets/Sakhiur/signal/resolve/main/data_in_brief.csv"

df = pd.read_csv(url)
print(df.shape)
df.head()

```

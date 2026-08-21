---
license: cc-by-4.0
task_categories:
- text-classification
language:
- en
---

# Curated Customer Reviews

2,000 deduplicated movie-review snippets with binary sentiment labels, curated from the upstream sentiment corpus.

## Origin

- **Source dataset**: `stanfordnlp/sst2`
- **Source license**: cc-by-4.0
- **Curated by**: Data Platform Team
- **Last audited**: 2026-08-20

## Content

Each row in `data.csv` contains one record. The dataset is published for research and evaluation purposes only.

## Usage

```python
import pandas as pd
df = pd.read_csv("data.csv")
print(df.head())
```

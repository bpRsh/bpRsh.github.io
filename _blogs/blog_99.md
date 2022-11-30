---
title: "Pandas Pivot Table"
collection: blogs
type: ""
venue: ""
date: 2022-11-30
location: "Carrollton, TX"
---

```python
df.groupby([A,B,col_pivot])[col_val].sum().unstack()\
  .add_prefix('sum_').rename_axis('',axis=1).reset_index()
```

---
title: "Pandas Datetime"
collection: blogs
type: ""
venue: ""
date: 2022-11-30
location: "Carrollton, TX"
---

```python
next_day = (datetime.today() + pd.DateOffset(days=1)).strftime("%Y-%m-%d")
```
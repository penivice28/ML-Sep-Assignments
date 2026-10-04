# ML Assignment 2: Pandas Messy Data Handling

## Repository Contents
- `assignment2_pandas.ipynb`: Jupyter notebook covering tasks 1 to 13 with all outputs displayed.
- `customer_transactions_messy.csv`: Raw public transactions dataset (>6,000 rows, 10 columns).
- `cleaned_data.csv`: Cleaned dataset in CSV format.
- `cleaned_data.parquet`: Cleaned dataset in compressed columnar Parquet format.
- `README.md`: Dataset source and benchmark figures.

## Dataset Source Link
- Dataset: `customer_transactions_messy.csv` (Public transaction records with mixed types, dates, missing values, duplicates)
- Source URL: `https://raw.githubusercontent.com/datasets/customer_transactions_messy.csv`

## Memory Saving and File Size Numbers
- **Initial In-Memory Usage**: ~710 KB
- **Optimized In-Memory Usage**: ~280 KB (**~60% memory savings**)
- **CSV Disk Size**: ~520 KB (Load time: ~18 ms)
- **Parquet Disk Size**: ~110 KB (Load time: ~4.5 ms, **~4x faster load time and 78% storage compression**)

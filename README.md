# finance_data
finance data used in class

# csv
df.to_csv("aapl_2023.csv", index=True)

df_loaded = pd.read_csv("aapl_2023.csv", index_col=0, parse_dates=True)

# parquet
df.to_parquet("aapl_2023.parquet")

df_loaded = pd.read_parquet("aapl_2023.parquet")

# pkl
df.to_pickle("aapl_2023.pkl")

df_loaded = pd.read_pickle("aapl_2023.pkl")


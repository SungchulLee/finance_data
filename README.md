# finance_data
finance data used in class

df.to_csv("aapl_2023.csv", index=True); 
df_loaded = pd.read_csv("aapl_2023.csv", index_col=0, parse_dates=True)


df.to_parquet("aapl_2023.parquet"); 
df_loaded = pd.read_parquet("aapl_2023.parquet")

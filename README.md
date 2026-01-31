Restaurant Analytics :
  End-to-end analytics pipeline simulating real-world food delivery workflows.
  Built a single source of truth from multiple heterogeneous data sources.
  Data Sources.
  Orders data from CSV files.
  Users data from JSON files.
  Restaurants data from SQL scripts executed via SQLite.

=> Engineering Approach :
    Executed SQL scripts programmatically using Python.
    Loaded all data into pandas DataFrames.
    Applied LEFT JOINs to retain all order records.
    Ensured reproducibility and clean re-runs of the pipeline.

=> Final Dataset :
  Output file: final_food_delivery_dataset.csv.
  Used as the only source of truth for analysis.
  Contains unified order, user, and restaurant information.
  Key Business Analysis.

=> Order trends and seasonality :
    User behavior and repeat ordering patterns.
    City-wise and cuisine-wise performance.
    Membership impact analysis.
    Revenue distribution and high-value user identification.

=> Tools Used :
    Python
    Pandas
    SQLite
    Matplotlib
    Seaborn
    Jupyter Notebook

=> Note :
    Raw CSV, JSON, and SQL files are not used after merging.
    All insights are derived only from the final dataset.

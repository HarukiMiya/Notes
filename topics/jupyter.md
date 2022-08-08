# Jupyter notebook

## What I learned:
### Import files
```
pandas.read_csv() # CSV file
pandas.read_excel() # Excel file
pandas.read_sql_table('table', create_engine('postgresql://postgres:pwd@localhost/db').connect()) (from sqlalchemy import create_engine) # SQL database (need to do: from sqlalchemy import create_engine)
pandas.read_json() # JSON file
```

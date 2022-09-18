##  Data Science

## Google Colab  Python  notebook

- https://colab.research.google.com/
- https://www.shanelynn.ie/python-pandas-read-csv-load-data-from-csv-files/

##  Code Sample

```python

# Load the Pandas libraries with alias 'pd' 
import pandas as pd 
# Find out your current working directory
import os
print(os.getcwd())
# Out: /Users/shane/Documents/blog
# Display all of the files found in your current working directory
print(os.listdir(os.getcwd())

# Read data from file 'filename.csv' 
# (in the same directory that your python process is based)
# Control delimiters, rows, column names with read_csv (see later) 
data = pd.read_csv("filename.csv") 

# Preview the first 5 lines of the loaded data 
data.head()

```



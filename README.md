# Reduce Memory Usage
## Objective 
This function has the objective of reducing the memory usage from pandas dataframe, by iterating through all the columns of the dataframe and modifying the data type. This little step can reduce a lot of memory on untreated dataframes.

## How to use it
The function has only one argument: a pandas dataframe. It will iterate through all the columns of the dataframe setting the correct data types for each column and return another dataframe that uses less memory. 

# Structure
```
reduce_memory_usage
├── src/  
|  └── reduce_memory.py  # Python file with the function
└── README.md
```

## Any Doubts
 - Contact me: denner.bocardi@gmail.com


# DataMunge

#### DataMunge is a python module that helps clean and organize data for analysis. It includes functions for handling missing values, removing outliers, encoding categorical variables, normalizing data, reducing dimensionality and removing duplicate rows. It can be used in data analysis projects to prepare data for further analysis.

## Installation
```bash
pip install DataMunge
```
## Functions

### `remove_outliers(data, column, threshold)`

Remove outliers from a given column of a dataframe

**Params**:

-   `data`: dataframe
-   `column`: string, column name
-   `threshold`: int, threshold value

**Returns**:

-   dataframe

### `handle_missing_values(data, strategy="mean")`

Handle missing values in a dataframe

**Params**:

-   `data`: dataframe
-   `strategy`: string, strategy for handling missing values (mean, median or mode)

**Returns**:

-   dataframe

### `encode_categorical_variables(data, columns)`

Encode categorical variables in a dataframe

**Params**:

-   `data`: dataframe
-   `columns`: list of strings, column names

**Returns**:

-   dataframe

### `normalize_data(data, columns)`

Normalize data in a dataframe

**Params**:

-   `data`: dataframe
-   `columns`: list of strings, column names

**Returns**:

-   dataframe

### `reduce_dimensionality(data, n_components)`

Reduce dimensionality of a dataframe using PCA

**Params**:

-   `data`: dataframe
-   `n_components`: int, number of components

**Returns**:

-   dataframe

### `remove_duplicates(data)`

Remove duplicate rows from a dataframe

**Params**:

-   `data`: dataframe

**Returns**:

-   dataframe


**File Structure**

```
|-- DataMunge/
	 |-- __init__.py
	 |-- functions.py
|-- tests/
	 |-- test_functions.py 
|-- setup.py 
|-- README.md 
|-- LICENSE
```

**Contribution**: Contributions are always welcomed. If you have any ideas for new features or improvements, feel free to open an issue or submit a pull request.

**Note**: 
 ```txt
 This module is designed to be flexible and adaptable to different types of data and use cases.
 It is important to understand the underlying assumptions and limitations of each function and how they apply to your specific data before using them. 
 It is also recommended to test the functions on a small subset of your data before applying them to the entire dataset.
```

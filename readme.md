# Test Datasets For Variable Type Identification Experiments

This repo is a collection of real world datasets for use in tests and experiements attempting to infer a variable's type by it's values and characteristics.

The repo contains three folders:

1. *datasets_raw* contains the untouched datasets.
2. *datasets_header_stripped* contains the datasets with any header or footer notes removed.
3. *datasets_variable_types* contains CSVs named <dataset_name>_VAR.csv, containing the respective datasets' columns with the variable types.

## Variable Types:

Each variable in each dataset has been coded as belonging to one type of variable:

- categorical
- empty
- unstructured
- continuous
- discrete
- datetime
- geo
- unique

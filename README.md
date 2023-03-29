# Analyse spreadsheet script

This script accepts a spreadsheet file with temperatures from the user and prints the mean temperature

## Dependencies:
pandas 
## Functions present:

- mean_temperature()
Args: data (pandas dataframe of air temperature measurements, deg C)
Returns: Mean air temperature in deg C
- get_spreadsheet_columns()
Args: file_loc (location of spreadsheet), print_columns (whether or whether not to print the columns to console)
Returns: List of strings useful for header column.

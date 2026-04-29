

---

## AIM:

To study data binning and data formatting techniques in Pandas including categorization, type conversion, sorting, and analysis of datasets.

---

## THEORY :

* '**pd.DataFrame():**' Creates a structured table (DataFrame) from dictionary or data.

* '**print():**' Displays output on the console.

* '**pd.cut():**' Divides continuous data into discrete bins or categories.

* '**bins:**' Defines the range intervals for categorization.

* '**labels:**' Assigns names to each bin category.

* '**df['new_column'] = pd.cut():**' Creates a new categorical column based on binning.

* '**df.dtypes:**' Shows the datatype of each column in the DataFrame.

* '**astype():**' Converts data from one datatype to another.

* '**df['col'].astype(float):**' Converts column values into float datatype.

* '**df['col'].str.upper():**' Converts all string values in a column to uppercase.

* '**round():**' Rounds numeric values to a specified number of decimal places.

* '**df.sort_values():**' Sorts the DataFrame based on a column.

* '**ascending=False:**' Sorts data in descending (high to low) order.

* '**ascending=True (default):**' Sorts data in ascending (low to high) order.

* '**df['col'].unique():**' Returns unique values from a column.

* '**value_counts():**' Counts frequency of each category in a column.

* '**Multiple binning:**' Applying `pd.cut()` on different columns to categorize different features.

* '**Categorical Data Analysis:**' Helps in grouping continuous data into meaningful ranges for interpretation.

---

## CONCLUSION :

In this experiment, we learned how to categorize continuous data using binning techniques in Pandas. We also performed data formatting operations such as datatype conversion, text formatting, and sorting. Binning helped in simplifying numerical data into meaningful categories like low, medium, and high. These techniques are essential for better data analysis and interpretation.

---

Notes

Mode imputation replaces missing values with the most frequent value
in a column.

Forward fill copies the previous valid value into a missing row; it
does not calculate the actual purchase date.

Age extraction with the provided regular expression returns the
first sequence of digits as a string. Convert the column to a
numeric type separately if numerical calculations are needed.

Re-export the dataset and refresh the Power BI data source whenever
the cleaned data changes.

Project Status

Completed: Initial data inspection, selected missing-value handling,
age-text extraction, gender standardization, and preparation of export
code.


Type the topic name "Errors" in column A and row 148,

Go to column B and row 148, and type the following function beside the "fx" input field:
=FILTER(B2:D147,D2:D147="St Elizabe",B2:B147="Bed & Breakfast

This will return the row containing the cell with the error, which in this case, is "St Elizabe"






Below is the syntax of the FILTER function:

FILTER(range, condition1, [condition2, …]):

range: This is the range of cells that you want to filter.

condition1: This is the columns/row (corresponding to the column/row of the dataset), that returns an array of TRUEs/FALSES. This needs to be of the same size as that of the range

[condition2]: This is an optional argument and can be the second condition for which you check in the formula. This again can be a column/row (corresponding to the column/row of the dataset), that returns an array of TRUEs/FALSES. This needs to be of the same size as that of the range.
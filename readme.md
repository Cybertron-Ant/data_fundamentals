

Type "sort latitude/longitude" column G row 149

Type the following function in column H row 149:
=sort(H2:I147,1,true,2,true)

select the range column h and row 2 through to column I and row 147

second argument is the first column(H) of the selected range

third argument is a Boolean(true/false), with "true" meaning to sort the first column in ascending order

optional fourth argument is the second column(I) of the selected range

optional fifth argument is a Boolean(true/false), with "true" meaning to sort the second column in ascending order




SORT(range, sort_column, is_ascending, [sort_column2, is_ascending2, …])


range is the group of cells that you want to apply the sort function on (the cells that you want to sort)

sort_column is the main column by which you want to sort the data in the range.

is_ascending specifies if the range should be sorted in ascending or descending order of the sort_column. It can either be TRUE or FALSE, with a FALSE representing a ‘descending’ order.


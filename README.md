**Data issues** found Duplicate entries in Order ID column.
Found one duplicate row. Missing values of city, Salesperson and channel.
Incosistent formatting for TEXTS,NUMBERS,DATES and PERCENTAGES in all the columns.
Require date was before order date.

**Cleaning rules**
All duplicate rows were removed based on ORDERID since it's unique.
All column haedings were formatted correctly.
All missing values for city ,saleperson, channel were handled. 
All the negative values were convertd to zero. 
Order date was corrected to be before require date.

**Assumptions**
It is assumed that the dataset is complete for the given context of analysis.
Assumed that statistical methods used for cleaning are appropriate for the data distribution. 
It is assumed that the source of the data is reliable and that entries were accurately recorded.

# Bank_Data_Encoding

A bank dataset was chosen. 
It was quite cleaned cause it lacked null values and had not much outliers
The outliers were preferred not to be removed because all the columns having outliers were significant
Removing it would totally change our analysis making it faulty.
The steps were as belows : 
1. Checking for null values
2. Check for ouliers using visual (prefereably a box-plot)
3. String Manipulation for data consistency
4. Data Type Conversion : Int were as it is and other dtype(objects were changed to categories cause Many ML algorithms work well when the dtype is of category
5. Visuals were looked upon for statistical finding
6. Lastly, Encoding were chosen as the last step for data analysis and first step for Machine Learning
7. We use Label Encoding when we have an ordinal data ( eg: high school, masters , phd) it can be ranked so, an intger representative perfectly encodes a data
8. But for nominal data like colors ( red blue ) one hot encoding is the best
9. We avoid mistaken encoding (one hot instead of label).
10. A model can predict the labels encoded by label encoding in a rank so we avoid it for nominal data
11. Eg : red : 1 , blue 2 (here blue>red) is not true but ML algorithms assume that so , we avoid such fault.
    

###2. Data Set Description. 
For this extended bakery dataset, the source website provides dataset with different number of records which are 1000, 5000, 20000 and 750000. 

Besides that, for each number of the dataset, the data was recorded in 2 different forms which are the sparse and the full binary form. 

Example of sparse dataset (1000-out1.csv):
```
7, 4, 12, 31, 36, 44, 48
```

First digit is the row number then followed by the product number.


Example of full binary dataset (1000-out2.csv):
```
8,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,0,0,0,0,0,0,0,0,0,0,0,1,1,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0
```

For the binary form, the number of column represent each product, while 0 and 1 gives you an idea of what product is in the certain record.
 
 
* **Preprocessing for the dataset**

Before the actual data mining process begin, all the empty spaces that is found within the sparse form of the dataset is replaced with null value which is not available. Besides that, all the product number that is found within each record is then replaced with the item name so that the rules generated are easier to describe and understand.


* **Decision to ignore**

There was one of the dataset which the source website provided that contains the information of quantity of the product that customer purchased. That information was not used in the data mining process due to the reason that we are not interested in the quantity of the item they bought and it is not needed to found out the combination of product that customer will buy in. 


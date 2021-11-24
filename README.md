# waterpota
This project is about clearing the data and finding the right classifier for finding water potability as a kaggle challenge.
The data is in the file water_potability.csv

The procedure to clear the data

1) Visualize the features in histogram and its statistical info
2) clear the data based on the abnormality and unknow value in the data and repeat the step 1.
3) Reducing the number of the features based on correlation between them

The groups of correlated features according to general preexisting knowledge
1) pH,Conductivity
2) hardness,solids,sulfates,chloromine or any two combo among these.

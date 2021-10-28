# 2017 & 2018 Stock Analyses with Refractored VBA Script
## Overview of Project
The purpose of this project is to refractor the original script in order to efficiently analyze stock performance by only looping thorugh the entire dataset once. Doing so will allow for the code to run faster, thereby allowing for it to be repurposed for large datasets. 

## Results
### Stock Performance in 2017 vs. 2018

![VBA_Challenge_2017-Stock-Performance.PNG](https://github.com/lexyzhong/stock-analysis/blob/main/Resources/VBA_Challenge_2017-Stock-Performance.PNG)

In 2017, all stocks except TERP had a positive return. DQ had the highest return with +199.4%, followed by SEDG with +184.5%, and ENPH with +129.5%.

![VBA_Challenge_2018-Stock-Performance.PNG](https://github.com/lexyzhong/stock-analysis/blob/main/Resources/VBA_Challenge_2018-Stock-Performance.PNG)

In 2018, all stocks except ENPH and RUN had a negative return. ENPH is the only stock that had a positive return in both years. ENPH also had the highest total daily volume in 2018. Overall, the data suggests that of the stocks analyzed, ENPH is the best investment choice.


### Original Script vs. Refractored Script
Both the original script and refractored script gave the same output. However, the refractored script executed almost 7x faster.

**Original:**

![VBA_Original_2017.PNG](https://github.com/lexyzhong/stock-analysis/blob/main/Resources/VBA_Original_2017.PNG)
![VBA_Original_2018.PNG](https://github.com/lexyzhong/stock-analysis/blob/main/Resources/VBA_Original_2018.PNG)

**Refractored:**

![VBA_Challenge_2017.PNG](https://github.com/lexyzhong/stock-analysis/blob/main/Resources/VBA_Challenge_2017.PNG)
![VBA_Challenge_2018.PNG](https://github.com/lexyzhong/stock-analysis/blob/main/Resources/VBA_Challenge_2018.PNG)

## Summary
Refractoring code presents several advantages and disadvantages:

**Advantages:**
- code will execute faster
- code will be better organized
- more efficient code is better suited for processing larger datasets

**Disadvantages:**
- longer to write as it is a multi-step process involving numerous cycles of coding and testing  
- risk of introducing bugs with new code

For this project, although the refractored code executed almost 7x faster than the original, the improvement is not as apparent to the user as the original script was already fast and ran in under a second. Therefore, with this dataset, refractoring the original script is not absolutely necessary. However, if we were to apply the scripts to larger datasets, the benefits of the refractored code will become apparent.

# Phase 4 Project - Real Estate Time Series

<img src='https://github.com/Andro-T/dsc-phase-4-project/blob/main/images/Oahu.jpg'>

Finding Investment Opportunities in Hawaii.

## Project Overview

Our Investment Consustancy has been approached to provide advice on which areas in Hawaii would be the best locations to invest into. 

**Measuring Success**

To measure this we will be focusing on Return on Investment (ROI) as the primary investment. ROI is used to measure the profitability of an event or investment and works on a relative basis (Amount Gained minus Amount Spent) divided by Amount Spent. This means that the absolute value of the property is not relevant for our investment decisions. If it turns out that surf shacks have the highest potential return, we will still recommend them.


### The Data

We will be using a dataset from Zillow covering housing data from 1996 till 2018. This data includes the Financial Crisis and will impact on how we approach the modeling. This data was split into just those covering Hawaii. The graph below shows the mean price in different zipcodes. There is a large disparity but the mean property value in 2018 was roughly $677,000. The standard deviation is quite high because of the very large range present in property values.

<img src='https://github.com/Andro-T/dsc-phase-4-project/blob/main/images/boxplot.png'>

### The Documents

- The model and all the preprocessing can be found in the student.ipynb file. 
- The presentation covering the findings can also be found as a pdf in this repository. 
- Images used can be found in the images file


### Conclusion

Best Four Zipcodes:
1. 96771 - Mean ROI: 35.9%	Bear Case: -15.45%	Bull Case: 87.25%
2. 96763 - Mean ROI: 31.1%	Bear Case: 3.12%	Bull Case: 59.08%
3. 96772 - Mean ROI: 28.65%	Bear Case: 1.33%	Bull Case: 55.97%
4. 96743 - Mean ROI: 21.11%	Bear Case: 0.77%	Bull Case: 41.46%

Worst Four Zipcodes:
1. 96760 - Mean ROI: -18.33%	Bear Case: -61.3%	Bull Case: 24.64%
2. 96779 - Mean ROI: -5.44%	Bear Case: -35.73%	Bull Case: 24.86%
3. 96785 - Mean ROI: -4.63%	Bear Case: -47.13%	Bull Case: 37.87%
4. 96752 - Mean ROI: -0.24%	Bear Case: -22.13%	Bull Case: 21.64%
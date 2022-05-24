# Green Stocks Analysis



## Overview of Project

For this project, the client requested analysis of stocks for Green/Eco-friendly companies, with specific interest in Daqo (DQ).  An analysis of other Green companies was also done for comparison of performance for 2017 and 2018. Code was refactored to be more efficient and adaptable.

## Results

The stock of interest, DQ, performed well in 2017 as did most other green stocks.  2018 was a different outcome for most green stocks, as the majority suffered a loss.  The stocks that continued to grow both years analyzeed were ENPH and RUN.  Based on this limited data set, the recommendation would be to diversify the client's portfolio with investments in ENPH and RUN.  SEDG had large gains in 2017 and very small losses for 2018.  It would be one to watch for additional years to assess investment potential.  

## Summary

The orignal code looped through the data multiple times to collect the data we needed to analyze in sections.  The refactored code ran multiple loops but collected the data all together which was more efficient as seen in the comparison of time taken for the code to run. Using the arrays and indices also allows the code to be more flexible if new years are added to the dataset.  

The refactored code for the year 2017 ran in  0.1757813 seconds and the original code for that year ran in 0.96875 seconds.

![](Resources_5CVBA_Challenge_2017.PNG)

The refactored code for year 2018 ran in 0.1328125 seconds and the orignal returned a time of 0.9492188 seconds.  Both years were improved by approximately 0.8 seconds.

![](Resources_5CVBA_Challenge_2018.PNG)

Refactoring code is useful to make code more efficient and clean.  The first code when working on a project is like a "rough draft".  Just like writing a report or article, the final draft is usually an improvement and flows better to more efficiently get your point across. Refactoring code is similar to this. It's an opportunity to improve.  With refactoring, the code may become easier to read and understand and also make it easier for the analyst doing the quality check on that code. Starting out as a new coder, the original code may be more intuitive and allow the person to move step by step to get to the answer needed.  It may be easier to find small mistakes as you build piece by piece.





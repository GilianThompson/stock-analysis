# stock-analysis

### Overview of Project
In this project, stock data of twelve different stocks was analyzed for 2017 and 2018 in order to draw conclusions about which green energy stocks might be more profitable than others to invest in. 

### Results
Initially, the clients want to invest in DQ New Energy Corp. A VBA script was written to analyze all the stocks in the data set for both 2017 and 2018, and can be seen below.

<img width="278" alt="Screen Shot 2021-06-22 at 9 40 11 PM" src="https://user-images.githubusercontent.com/85901073/123022214-76ba8f80-d3a3-11eb-88c8-dd20a2390f54.png">

<img width="276" alt="Screen Shot 2021-06-22 at 9 40 48 PM" src="https://user-images.githubusercontent.com/85901073/123022241-820dbb00-d3a3-11eb-9012-80cdb960936b.png">

'Total Daily Volume' was calculated by summing the each stocks' volumes, and 'Return' was calculated by finding the difference in closing price versus starting price of each stock throughout the year. Looking at the first table, in 2017 all the stocks except for TERP saw an increase in stock price, including DQ. However, in 2018, all but two of the twelve stocks saw price declines, some more than others. From this, ENPH and RUN could be profitable stocks to invest in since they are the only ones that saw an increase in stock price during both years that were used for the analysis. Out of the two, ENPH might be the better stock to invest in since the return increased significantly both years. ENPH saw a return of 129.52% in 2017 and 81.92% in 2018 whereas RUN had a return of only 5.55% in 2017 and then 83.95% in 2018. 

The initial VBA script was written to analyze the given twelve stocks for 2017 and 2018, but it was refactored so that it could process larger data sets quicker. The first time around, the script had run times of approximately 0.8 seconds. The refactored code, however, was able to run in approximately 0.164 seconds for the 2017 data set and in 0.180 seconds for the 2018 data set. Thus, refactoring the code proved to increase efficiency which will be useful in handling larger data sets. 

### Summary
Refactoring the code has the advantage of making code more efficient compared to the first time around when perhaps the execution of the script has more importance than, for example, the run times, structure, and/or readability of the code. However, a disadvantage to refactoring is that time is spent going over and rewriting the same piece of code, and that new bugs could be introduced to the script that might not be caught until runtime. 


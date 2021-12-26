# VBA_Challenge
Stock Analysis with EXCEL and VBA. 

## Overview of Project
The purpose of this analysis is to analyze the data from the Stock Market dataset with VBA code to loop throughout the data and return. The request is from a client named Steve. We are calculating the volume and the return value for stock for the stock tickers of 2017 and 2018. After analyzing we will be able to advise Steve which stock is the best to invest in. In order to make the code more efficient we will edit or refactor the code and cut down the processing time.  
## Results about analysis of the stock: 
The analysis of the stocks in 2017 and 2018 shows the following results.
<img width="174" alt="All Stocks 2017" src="https://user-images.githubusercontent.com/95591222/147421692-e4c35a47-1c19-449b-b3d7-be0f43ddf096.png">
<img width="170" alt="All Stocks 2018" src="https://user-images.githubusercontent.com/95591222/147421694-3eb9d1ed-a013-4490-b35c-f7a71f0edc54.png">
 
The stock ENPH and RUN have been positive for both 2017 and 2018. ENPH has the highest return of about 129% in 2017 and about 82% in 2018. In fact by looking at the data the stock ENPH has a return of above 80% in 2018 when almost all 12 stocks had a negative return.

## Results about reduce processing data time

In our first approach, we defined the stock DQ and created a ticker to get the year, volume, and the return, ( the starting price and ending price). The code runs over and over with every id of the stock ticker of the dataset has.

 <img width="279" alt="Picture1" src="https://user-images.githubusercontent.com/95591222/147421714-7a495e28-c17c-4c5c-ac4d-f6dceabd504d.png">

#### ID Array

The tinker index is set equal to zero before looping over the rows and the list of tickers name’s looks like:

 <img width="197" alt="Picture2" src="https://user-images.githubusercontent.com/95591222/147421732-1da88dd8-4cf9-4cc6-a6b3-a683f0abbe05.png">
<img width="206" alt="Picture3" src="https://user-images.githubusercontent.com/95591222/147421735-44378ec1-9a9a-4ae1-a5b8-abe812acd13b.png">

 
The time in the data processing in our first approach had an average of 4.8 seconds. After refactoring it was at .65 seconds. That additional saved us over 4 seconds of processing time. 
 
   <img width="152" alt="VBA Challenge 2017" src="https://user-images.githubusercontent.com/95591222/147421741-ad7e2f60-73b7-4b83-9e00-1121eb5f0853.png">
<img width="149" alt="VBA Challenge 2018" src="https://user-images.githubusercontent.com/95591222/147421743-ac00565f-7f22-422d-a339-4d3df2790877.png">

After Refactoring:
 
 <img width="377" alt="VBA Challenge 2017 Refactored" src="https://user-images.githubusercontent.com/95591222/147421746-72ace02a-6002-4805-bd0f-74b2da369c28.png">
<img width="373" alt="VBA Challenge 2018 Refactored" src="https://user-images.githubusercontent.com/95591222/147421750-63125578-bc12-4016-a393-752895f6b00d.png">


## Summary: 
As you can see from the results the advantage of refactoring is that it improves the processing data time. It allows us to create clean solutions in well coded structure. The disadvantage of refactoring code is that it takes more time to plan and design a solution. It is also easy to add more stock tickers and increase our data set without a lot of changes in the code. 

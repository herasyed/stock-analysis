# stock-analysis
performing analysis on stock data


## Overview of the Project
Steve wants to expand the dataset to include the entire stock market over the last few years. Our code works well for a dozen stocks but it will take longer if we were to analyze thousands. In this challenge we had to refractor the original code to loop through all the data one time in order to collect the same information as before as well as make the the VBA script run faster so it can be capable of looking at more than a dozen stocks quickly.


## Analysis
The refractored code successfully cut down on the time it took for our code to run through the stock information. The original code took 0.289 seconds while the refractored code took 0.0859 seconds - screenshots below:

<img width="341" alt="VBA_Challenge_2017_Original" src="https://user-images.githubusercontent.com/88937178/131275576-174660d8-4786-4403-bdaf-5fa404ea3c96.png"><img width="328" alt="VBA_Challenge_2018_Original" src="https://user-images.githubusercontent.com/88937178/131275608-73cf0fbe-0f9d-4cdb-b8f0-11c4f3eb3888.png">

<img width="279" alt="VBA_Challenge_2017_Refractored" src="https://user-images.githubusercontent.com/88937178/131275586-b9eb0dc7-7896-4d79-bc93-c97852748464.png"><img width="270" alt="VBA_Challenge_2018_Refractored" src="https://user-images.githubusercontent.com/88937178/131275624-bbce7d89-248c-4aa0-a111-dab01cd8e2e0.png">


## Summary

### Advantage and Disadvantage of Refractoring 
The primary advantage of refractoring code is that it dereases the run time and memory space needed to run the macro. It is also helpful to have all of the code in one, easy to read place. A disadvantage arises when the original code is unclear or poorly written - making the act of refractoring very difficult.

### Advantage of Our Refractored Code
The refractored code has a significantly shorter run time, which will benefit Steve immensely as he analyzes larger numbers of stocks.

# Stock-analysis

## Overview of Project
Analyzing stock information from 2017 & 2018 for our hypothetical friend, Steve, to present to his first clients - his parents. This analysis will show Steve which stocks are worth investing in or avoiding. 

### Purpose
The purpose of this project was to analyze stock information for our friend Steve, so he can present it to his first clients, his parents. In order to properly analyze the stock information, we had to refactor the Module 2 solution code to collect specific stock information for the years: 2017 & 2018. Once the information was collected, the goal was to analyze the data to determine if the stocks should be invested in or avoided. 

## Results
Below will show the exact code used for analysis:

![All_Stock_Analysis_Refactored_Code pt1](https://user-images.githubusercontent.com/95371617/148290873-c056b5ee-4a8d-46e6-b88d-5a023d81859e.png)

![All_Stock_Analysis_Refactored_Code pt2](https://user-images.githubusercontent.com/95371617/148290889-0fd5bc11-494b-4e9a-aa5b-9d42a9aff18a.png)

![All_Stock_Analysis_Refactored_Code pt3](https://user-images.githubusercontent.com/95371617/148290906-d3f3daa9-b865-4542-92c2-c0ad61c90eb4.png)


There is a clear difference between the stock performance of 2017 and the stock performance of 2018, 10/12 stocks performed better in 2017 than in 2018. The ten stocks that did better in 2017 (AY, CSIQ, DQ, ENPH, FSLR, HASI, JKS, RUN, SEDG, SPWR, TERP, & VSLR) had an average return difference of 99.06% from 2017 to 2018.	4 stocks (DQ, FSLR, JKS, & SEDG had over 100% return difference from 2017 to 2018. Of the two stocks that did better in 2018 - TERP & RUN, RUN is the only stock to actually do well in the new year. TERP had a -7.2% reutrn in 2017 & -5.0% return in 2018, while RUN had a +5.5% return in 2017 and an 84% return in 2018. To Calculate the return difference in stocks you either add or subtract the 2017 return from the 2018 return. For example, to calculate the return difference for DQ, you would add the 2017 return (+199.4%) to the 2018 return (-62.6%) to get a 262% return difference. I think it's important to highlight DQ for Steve because his parents have been very high on the DQ ticker since they started investing, because their first date was in a Dairy Queen. 

For reference, see stocks below:

![Refactored_Stocks_2017](https://user-images.githubusercontent.com/95371617/148290942-2e99fcaf-1c21-41a6-a3e5-3990169cc8d4.png)

![Refactored_Stocks_2018](https://user-images.githubusercontent.com/95371617/148290958-7442a851-fbee-4867-8c6c-41774b4d068a.png)

An additional point of emphasis should be made for the execution time difference of the original script vs the refactored script. The 2017 original script execution took .5625 seconds, which is .3399 slower than the 2017 refactored script execution, .2226563 seconds. The 2018 original script execution took .5273438 seconds, which is .4141 seconds slower than the 2018 refactored script execution, .1132813 seconds.

![Original Script 2017](https://user-images.githubusercontent.com/95371617/148293475-707bae77-2c34-47d3-8a65-de06bbd632c9.png)

![VBA_Challenge_2017](https://user-images.githubusercontent.com/95371617/148293496-9f0dfa99-7eb9-43b3-97d1-4b2231bc191a.png)

![Original Script 2018](https://user-images.githubusercontent.com/95371617/148293527-31f2cc4b-7f2d-4411-a94a-b250a88b0382.png)

![VBA_Challenge_2018](https://user-images.githubusercontent.com/95371617/148293547-b806622c-0b45-495c-8774-8b471581f6a0.png)


## Summary
# What are the advantages or disadvantages of refactoring code?
Refactoring code has plenty of advantages; however, there are a clear top two. The first advantage of refactoring code is that it runs much faster, increasing efficency and speeding up the entire process for anyone involved. The second advantage of refactoring code is that it makes the programming much cleaner and easier to read, allowing users who are unfamiliar with the code or who have not seen it in an extended period of time to jump right in and have a clear understanding of everything that is happening.

# How do these pros and cons apply to refactoring the original VBA script?
The first advantage, running much faster, applies to the original VBA script in a way that everyone can understand. Before refactoring, the original 2017 execution took .5625 seconds and the original 2018 execution took .5273438 seonds, which aren't bad but aren't comparable to the execution time for the refactored scripts. The 2017 refacotred script only took .2226563 seconds (61% faster) and the 2018 refactored script only took .1132813 seconds (79.6% faster). For everyday tasks, half a second vs a quarter of a second isn't a tremendous difference; however, when the goal is efficency refactored scripts are clearly better. 

# Stocks-Analysis
Using VBA to analyze the best stocks of a dataset
## Overview of Project
The main goal of the stocks analysis project is to help Steve analyze a selected number of stocks to see which ones his parents should invest in. We have a list of 12 stocks and using VBA we will see the percentage return on the stocks and the total volume of the selected stocks for 2 separate years. We are creating the code in a way so that Steve can easily click a button to run the analysis and can quickly see which stocks performed the best in either 2017 or 2018; something that Steve can choose the year before the analysis is run. 
## Results
When the macro is run, using the All Stocks Analysis Refactored code, Steve is prompted to choose the year to run the analysis on; 2017 or 2018. The code for Steve to see the prompt is found by typing yearValue = InputBox(“What year would you like to run the analysis on?”). If Steve starts with 2017, you can see based on the image seen here [2017 image,<img width="536" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/100726716/158465851-b0049c7d-7e66-4445-b8f6-25ffac788bcc.png">
] that the code takes roughly 0.2 seconds to run. You can also see, because we formatted the code to display green for positive percentages show as an If Then statement in the code as If Cells(I, 3) > 0 Then Cells(i, 3).Interior.Color = vbGreen and a red display for negative percentages, most of the returns in 2017 are positive. Alternatively, if Steve wants to run the 2018 analysis shown in this image, <img width="467" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/100726716/158466097-370afce5-4bf4-4eec-931e-2c6df9c02955.png">
 he will see majority of the returns are negative as well as the code taking about 0.2 seconds to run.  
###  Differences in the Execution Times
On my computer, the execution times from the original script to the refactored script varied by more than a second. To run the 2017 and 2018 original script, the timer states it takes around 1.2 seconds to run. And as shown in the images previously, the refactored script takes about a second slower at roughly 0.2 seconds. 

## Summary 
### What are the advantages or disadvantages of refactoring code?
The clear advantage of the refactored code is the time it takes the computer to run the code is less time than the original script. When dealing with large data sets that run more loops than our 12 loops, I can imagine that would put a huge strain on the machine if the code were long and tedious. Another advantage of the refactored code is quite simply the code is much more concise and easier to read. The original script is redundant and more confusing to read once you understand how to read the code. 
A disadvantage to the refactored code is without a prior knowledge of VBA, and a true understanding of what you are doing, the refactored code would seem to skip steps. I had a hard time at first completing the module until I learned in plain language how to understand the original script. So, if you do not understand the long form from the original, I would say the refactored code does little use. 
### How do these pros and cons apply to refactoring the original VBA script?
In the specific pros to this data set, with the 12 loops my computer was able to complete the analysis much quicker and almost instantaneously. The code itself is not that complex with the refactored code. There isn’t a need for a nested loop, and the i loop is enough to suffice, which makes the code easier to read. In terms of the cons, the time it took me to complete the refactored code was a good amount of time, because I needed to fully grasp the original code before I could shorten and refactor the code. But, even that could be seen as an advantage because I now feel as though I have a better understanding of VBA. 

# Stock Analysis

## Overview
This project was to evaluate different stocks and their performance over a 2-year span: 2017 and 2018.  This report will help an investor make educated decisions on stock to buy, or not buy.

## Results
The charts below show the volume traded and ROI for each year.  Overall, the year 2017 was a much better year for ROI than 2018; although, stocks ENPH and RUN performed well in both years and TERP under-performed in both years.

![ROI_2017.png](https://github.com/WagnerLisaK/Stock-Analysis/blob/main/Resources/ROI_2017.png)

![ROI_2018.png](https://github.com/WagnerLisaK/Stock-Analysis/blob/main/Resources/ROI_2018.png)

## Code Structure
This data was analyzed with two different sets of code: one looping multiple times over the same data and one looping just once over all of the data. Below shows the 2 different sets of code ...

**The MULTIPLE-loop code is below:**
![Multi_Loop_Code.png](https://github.com/WagnerLisaK/Stock-Analysis/blob/main/Resources/Multi_Loop_Code.png)

**The SINGLE-loop code is below:**
![Single_Loop_Code.png](https://github.com/WagnerLisaK/Stock-Analysis/blob/main/Resources/Single_Loop_Code.png)


## Code Performance
The single-looping code out-performed the multiple-looping code as seen below.

**Below shows the MULTIPLE-Looping Run-time Results for 2017 and 2018 using only one array.**

![VBA_Challenge_2017_BEFORE.png](https://github.com/WagnerLisaK/Stock-Analysis/blob/main/Resources/VBA_Challenge_2017_BEFORE.png)

![VBA_Challenge_2018_BEFORE.PNG](https://github.com/WagnerLisaK/Stock-Analysis/blob/main/Resources/VBA_Challenge_2018_BEFORE.png)


**Below shows the SINGLE-Looping Run-time Results for 2017 and 2018 using four arrays.**

![VBA_Challenge_2017.png](https://github.com/WagnerLisaK/Stock-Analysis/blob/main/Resources/VBA_Challenge_2017.png)

![VBA_Challenge_2018.png](https://github.com/WagnerLisaK/Stock-Analysis/blob/main/Resources/VBA_Challenge_2018.png)


## Summary
Refactoring code can give the user a more efficient experience, but from a developer stand-point, it can be confusing and easy to make mistakes when moving the code around and adding/changing variables.  The refactored code may take more debugging time.  It may save time being able to copy/paste code, but extra diligence is needed to make sure the correct code ends up in the correct spot with the correct variables.

In my experience of refactoring the original code, I really had to take my time and found that I made many sloppy mistakes (incorrect variables, mis-ordered code) that were found during the debugging process.  If time allows, really thinking through the process, mapping out the code plan, and writing the code once is ideal.

Submitted by Lisa K Wagner, 06/30/2021


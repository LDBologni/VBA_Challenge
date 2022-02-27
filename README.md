# VBA_Challenge

## Overview of the Project

The purpose of the project is to analyze the information on a set of stocks from the years 2017 and 2018. The analysis was completed by using VBA to automate calculation tasks and provide information on green alternative energy stocks to potentially invest in (DQ). 

## Results

The data set contains two sets of data for over two years 2017 and 2018. By using VBA, the information is pulled from the two worksheets (2017 and 2018) that contained the stock information for twelve companies. 

The information is provided as follows, company’s ticker, date of exchange with the opening price, the highest and lowest price for the day, closing price the adjusted close and the volume traded. 
The macro provided the results of companies with the information previously given. The user must choose the year in order to get the results.

The result for the 2017 is as follow (See graph)

![VBA_Challenge_2017_Results](https://user-images.githubusercontent.com/98929742/155899324-19593232-69fc-4863-95de-cdc4163991ce.JPG)

As the graph shows, the year 2017 had a positive return in the majority of stocks (TERP Negative). Providing an average return of 67.3%, meaning that it was a good year for investors of green alternative energy. DQ had an impressive 199.4% return, which is no surprise why Steve’s parents would want to invest in.

The result for the 2018 is as follow (See graph)

![VBA_Challenge_2018_Results](https://user-images.githubusercontent.com/98929742/155899971-377ee606-b626-4e4d-a0fa-d300e64ae18e.JPG)

As the graph shows, the year 2018 had a negative return in the majority of stocks (ENPH, RUN Positive). Providing an average return of -8.5%, meaning that it was a bad year for investors of green alternative energy. DQ had a drop of 62.6% return. This could be caused due to new alternative energy sources, or the green alternative energy is not as efficient as it was expected.

By refactoring the code the results are as follow:

- For the year 2017 before refactored

![Running_Code_Time_2017_Before_Refactored](https://user-images.githubusercontent.com/98929742/155901310-223fce9a-eaac-4ccc-a17c-a3006abeaea6.JPG)

- After refactored

![Running_Code_Time_2017_Refactored](https://user-images.githubusercontent.com/98929742/155901325-3fb7f68b-7365-46c9-abe3-89a8368890e9.JPG)

Both time results are imperceivable for the human being.

- For the year 2018 before refactored

![Running_Code_Time_2018_Before_Refactored](https://user-images.githubusercontent.com/98929742/155903251-e36c00b4-2878-4a8d-9deb-8e494742693b.JPG)


- After refactored

![Running_Code_Time_2018_Refactored](https://user-images.githubusercontent.com/98929742/155903258-e59ba7bd-a439-4020-aaef-0e99900c13c5.JPG)


Same results as the 2017. Because of the size of the file, the run time is very short and imperceivable by humans, but in large data sets the gap difference could increase between them. I would make sense that the refactored code takes longer time than the not refactored, because we are adding loops in the code and that would require more processing time. 

## Summary

As previously explained, it would depend on how the code is going to be refactored. Meaning that more tasks could be added, or tasks could be removed. Having a base code would reduce the amount of time typing the code but adding more and more tasks might cause that the base code would no longer work.

In this cause, refactored the code did not interfere with the purpose of the project, in fact it helps displaying the data better for the user, a downside is that it affected the processing time, but since the data sheet is not big enough it would not cause a problem.




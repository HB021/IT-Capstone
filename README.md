# IT-Capstone Project    
This repository explores the step by step development of a prototype of an AI model that predicts a dropout rate of students trying to major in  certain subject. Note: The dataset is a sample dataset that is generated using statistical figure. Therefore, we do not expect the result to be accurate with the general population.   

# Links to different articles used for assumptions and bases for creating datasets:  
  
Link to the data sheet:  
https://docs.google.com/spreadsheets/d/1hfLxRmMwhd4Pa5tXfjiEVgP7JZPAq_MP4LY_-WhHbQo/edit?usp=sharing  

  # Creating the dataset:
    First and Last names: First, I generated 7000 rows of first and last names using ChatGPT. 
    Legal Gender: Then, I prompted ChatGPT to add another column named "Legal Gender" and fill it up with values of either Male or Female, but restricting the total number of males to be 42% of the total population. The reference to this statistic has been taken from PewResearch.    Link: https://www.pewresearch.org/short-reads/2023/12/18/fewer-young-men-are-in-college-especially-at-4-year-schools/#:~:text=Today%2C%20men%20represent%20only%2042,balance%20has%20not%20changed%20much.
    
Characterizing SAT scores:  https://www.kaptest.com/study/sat/whats-a-good-sat-score/#:~:text=What%20Is%20a%20Good%20SAT%20Score%3F%20%282023-2024%29%201,is%20the%20maximum%20score%20of%201600.%20More%20items
  Three categories:  Below average (0) : Less than 1028 (according to the average scores of 2023),  Above average (1): 1028-1600   

  Characterizing Pell Grant Status:  Potential Pell Grant Recipient (1) : Annual Family Income less than $60,000, Non-Pell Grant Recipient (0) : Annual Family income more than $60,000  

  Characterizing total percentage of dropout rates in general and with respect to White population:  https://research.com/universities-colleges/college-dropout-rates#:~:text=While%20high%20school%20dropout%20rates,issue%20(ThinkImpact%2C%202021)

  



# IT-Capstone Project    
This repository explores the step by step development of a prototype of an AI model that predicts a dropout rate of students trying to major in  certain subject. Note: The dataset is a sample dataset that is generated using statistical figure. Therefore, we do not expect the result to be accurate with the general population.   

# Links to different articles used for assumptions and bases for creating datasets:  
  
Link to the data sheet:  
https://docs.google.com/spreadsheets/d/1hfLxRmMwhd4Pa5tXfjiEVgP7JZPAq_MP4LY_-WhHbQo/edit?usp=sharing  

  # Creating the dataset:
  First and Last names: First, I generated 7000 rows of first and last names using ChatGPT. 
  Legal Gender: Then, I prompted ChatGPT to add another column named "Legal Gender" and fill it up with values of either Male or Female, but restricting the total number of males to be 42% of the total population. The reference to this statistic has been taken from PewResearch.    
  Link: https://www.pewresearch.org/short-reads/2023/12/18/fewer-young-men-are-in-college-especially-at-4-year-schools/#:~:text=Today%2C%20men%20represent%20only%2042,balance%20has%20not%20changed%20much.
  Then I created a column Enrollment Year, Graduation Year, Dropout Year, and Ethnicity. The values for thesehave been filled using the statistics given in the links below:
  https://nscresearchcenter.org/stay-informed/?gad_source=1&gclid=Cj0KCQjwqdqvBhCPARIsANrmZhP1AXzynXaJQIne75yupaH8g9G-kB11tOMv-JS1GHuxaeeI-zFMWHUaAsjnEALw_wcB
  https://en.wikipedia.org/wiki/Race_and_ethnicity_in_the_United_States

  Then, I generated another column with the title "Work Status". The distribution given in the data is distributed such that the status is divided as 5% for "full-time," 45% for "part-time," and 50% for "no work." 
    
 Link to income status: https://www.census.gov/library/publications/2023/demo/p60-279.html  

  Characterizing Pell Grant Status:  Potential Pell Grant Recipient (1) : Annual Family Income less than $60,000, Non-Pell Grant Recipient (0) : Annual Family income more than $60,000  

  Characterizing total percentage of dropout rates in general and with respect to White population:  https://research.com/universities-colleges/college-dropout-rates#:~:text=While%20high%20school%20dropout%20rates,issue%20(ThinkImpact%2C%202021)

  



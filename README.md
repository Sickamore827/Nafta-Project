# North America before and after NAFTA

## Overview

- probelm statement - NAFTA is the North America Free Trade Agreement. NAFTA was implemented in 1994 opening up the trading   borders between Canada, Mexico, and the United States. I'm looking into the correlation bewtween North Americas GNI and life expectancy before and after NAFTA was implemented
- NAFTA is responsible for shaping Americas economy in the late 1990's and early 2000's. elimanting tarrifs and invesment regulations that were formally in place restricting trading among North American Countries. This agreement was supposed to boost all economies involved. 
- Americas economy was boosted momentarily by NAFTA, later creating a larger divide in the middle class. I want to see how other countries were affected by this agreeement, and how their life expectancy was potentiallly affected.
- My outcomes were mixed. Americas GNI between 1973 and 1994 were increased by 37% while between 1994 and 2014 they only increased 35%. A lower rate of increase between the 20 year period. Canada saw a greater increase in GNI, seeing an almost 40% higher increase in their GNI before and after NAFTA. While Mexico saw the worst of the deal. only increasing 35% a much worse outcome from their 178% from 1973 to 1994. Life expectancy also generally followed the trends of GNI. Mexico seeing a sharp increase in life expectancy when their economy was going from 1974 to 1994, then plateauing after the implementation of NAFTA.

---

## Data

All dataframes I used were ones given in folders.
- life_expectancy.csv
- gni_per_cap_atlas_method_con2021.csv
    

|Feature     |Type |Dataset   |Description                  |
 ------------|-----|----------|-----------------------------|
|before_nafta|int  |gni       |% of growth before NAFTA     | 
|after_nafta |int  |gni       |% of growth after NAFTA      | 


## requirments

- python 3
- jupyter 
- pandas
- matplotlib.pyplot


## Executive summary
NAFTA was introduced as a way to boost all three countries economies. I was looking at the GNI data set to determine whether every country benefited from the agreement. 
## Methods
- What did you do? How did you change the data? why?
I created separate variables for different time periods. I created a function to find the percentage of change between the years 1974-1993 and 1994-2014. While finding global average for year 1974, 1994, and 2014.
- Explain yourself. How did this contribute to your goal
Finding these percentages helped me understand the GNI growth before and after NAFTA
## Findings
NAFTA seemed like a loop hole for America to send over manufactruing jobs for cheaper labor. It's difficult to determine how it affected America exaclty, but a lower perectange of increase of GNI from 1994 to 2014 then the 20 years prior, is an indicator that we did not see the growth in the middle class they promised. 

## Sources
-https://www.cbp.gov/trade/north-american-free-trade-agreement#:~:text=North%20American%20Free%20Trade%20Agreement%20(NAFTA)%20established%20a%20free%2D,produced%20by%20the%20signatory%20nations.

-https://www.thecanadianencyclopedia.ca/en/article/north-american-free-trade-agreement-nafta
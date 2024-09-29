This project aims to analyze survey data to determine which factors influence a driver's decision to accept coupons for restaurants, bars, or coffee shops along their route.

**Jupyter Notebook can be found at:**
[https://github.com/sraghav2000/customer_coupon_acceptance/cusomer_coupon_acceptance.ipynb]

**Data set Used can be found at:** 
[https://github.com/sraghav2000/customer_coupon_acceptance/coupons.csv]

**Dataset analysis:**

- Dataset contained 12684 rows, and a total of 26 columns
- Dataset contained '13370' null values among the following 6 columns 
car                     12576
Bar                       107
CoffeeHouse               217
CarryAway                 151
RestaurantLessThan20      130
Restaurant20To50          189

- 'car' column contained over 99% null values when compare to other 5 columns of 1% of null values

- Since the 'car' column has over 99% null values this column was ignored to concentrate on other columns. Missing values in the 'Bar', 'CoffeeHouse', 'CarryAway', 'RestaurantLessThan20', 'Restaurant20To50' columns of the DataFrame was filled with the data that was most frequently occurring value in the respective columns. This is a very common technique used in data preprocessing to handle missing data by replacing it with a representative value, in this case, the mode (most frequent value).

- There were about 74 duplicate rows of data found

**Observations related to Bar coupon:**

- Proportion of total observations that accepted the coupon: 56.76%
- Proportion of bar coupons accepted: 41.00%
- Proportion of bar coupons NOT accepted: 59.00%
- Acceptance rate for those who went to a bar 3 or fewer times a month: 37.05%
- Acceptance rate for those who went to a bar more than 3 times a month: 76.88%
- Acceptance rate for drivers who go to a bar more than once a month and age over 25: 69.52%
- Acceptance rate for all other drivers: 33.46%
- Drivers over 25 who go to a bar more than once a month have a higher acceptance rate
- Acceptance rate for drivers who go to a bar more than once a month with valid passengers: 71.32%
- Acceptance rate for all other drivers: 41.07%
- Drivers with valid passengers who go to a bar more than once a month have a higher acceptance rate.
- Acceptance rate for drivers who go to bars more than once a month, have valid passangers, and are not widowed: 71.32%
- Acceptance rate for drivers who go to bars more than once a month and are under 30: 72.17%
- Acceptance rate for drivers who go to cheap restaurants more than 4 times a month and have income less than 50K: 45.76%
- Group 2 has the highest acceptance rate

**Key Findings of Bar coupon:**

1.	Social Dynamics: Individuals who frequent to bar may exhibit a greater inclination for accepting promotional offers, suggesting a correlation between social behavior and coupon acceptance.
2.	Generational Preferences: Younger demographics may demonstrate a higher likelihood of engaging with novel experiences, including the utilization of promotional coupons, potentially indicating a generational trend in consumer behavior.
3.	Economic Considerations: Individuals who frequent to budget-friendly establishments and possess lower income levels may be more inclined to accept promotional offers as a means of cost-saving, suggesting a strong economic influence on coupon acceptance.
4.	Group Dynamics: Disparities in coupon acceptance rates among different demographic groups may highlight specific characteristics that foster a more receptive environment for promotional offers, suggesting the potential for targeted marketing strategies.


**Observations related to CoffeeHouse coupon:**

- Proportion of total observations that accepted the coupon: 56.76%
- Proportion of CoffeeHouse coupons accepted: 49.86%%
- Proportion of CoffeeHouse coupons NOT accepted: 50.14%
- Acceptance rate for those who went to a CoffeeHouse 3 or fewer times a month: 44.87%
- Acceptance rate for those who went to a CoffeeHouse more than 3 times a month: 67.50%
- Acceptance rate for drivers who go to a CoffeeHouse more than once a month and age over 25: 63.81%
- Acceptance rate for all other drivers: 42.69%
- Drivers over 25 who go to a bar more than once a month have a higher acceptance rate
- Acceptance rate for drivers who go to a CoffeeHouse more than once a month with valid passengers: 66.08%
- Acceptance rate for all other drivers: 49.45%
- Drivers with valid passengers who go to a CoffeeHouse more than once a month have a higher acceptance rate.
- Acceptance rate for drivers who go to CoffeeHouse more than once a month, have valid passangers, and are not widowed: 66.08%
- Acceptance rate for drivers who go to CoffeeHouse more than once a month and are under 30: 68.93%
- Acceptance rate for drivers who go to cheap restaurants more than 4 times a month and have income less than 50K: 53.76%
- Group 2 has the highest acceptance rate

**Key Findings of CoffeeHouse coupon:**

1.	Social Dynamics: Individuals who frequent to CoffeeHouse may exhibit a greater inclination for accepting promotional offers, suggesting a correlation between social behavior and coupon acceptance.
2.	Generational Preferences: Younger demographics may demonstrate a higher likelihood of engaging with novel experiences, including the utilization of promotional coupons, potentially indicating a generational trend in consumer behavior.
3.	Economic Considerations: Individuals who frequent to budget-friendly establishments and possess lower income levels may be more inclined to accept promotional offers as a means of cost-saving, suggesting a strong economic influence on coupon acceptance.
4.	Group Dynamics: Disparities in coupon acceptance rates among different demographic groups may highlight specific characteristics that foster a more receptive environment for promotional offers, suggesting the potential for targeted marketing strategies.

**Key Findings of Comparison of "Bar" goers vs "Coffee House" goers:** 

When compared the Acceptance rates
- "Frequent visitors not widowed" group's Bar accpetance is more than CoffeeHouse accpetance
- "Frequent visitors under 30" group's Bar accpetance is more than CoffeeHouse accpetance
- "Frequent visitors income under 50K" group's Bar accpetance is less than CoffeeHouse accpetance

**Next Steps and Recommendations**

These hypotheses provide a framework for further exploration of the factors influencing coupon acceptance, potentially leading to more effective marketing campaigns tailored to specific demographic segments. More in-depth analysis of different groups and various modeling techniques may provide clear patterns to tailor the coupons and market them more effectively 




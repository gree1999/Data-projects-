<h3>STUDY ON ANALYSIS OF CUSTOMER BEHAVIOUR IN ZOMATO</h3>
<h4>(A food delivery app)</h4>

<h3>Introduction</h3>
Zomato is an Indian multinational restaurant aggregator and food delivery company. It was founded by Deepinder Goyal and Pankaj Chaddah in 2008. Zomato provides information, menus and user-reviews of restaurants as well as food delivery options from partner restaurants in more than 1,000 Indian cities and towns, as of 2022–23. Zomato rivals Swiggy in food delivery and hyperlocal space.
Zomato was founded as FoodieBay in 2008 by Deepinder Goyal and Pankaj Chaddah who worked for Bain & Company. The website started as a restaurant-listing-and-recommendation portal. They renamed the company Zomato in 2010 as they were unsure if they would "just stick to food" and also to avoid a potential naming conflict with eBay.

<h3>Filters used in the data</h3>

*	Removed prefer to say no option in marital status field.
*	Created a calculated field for weekdays.
*	Grouped the ages into 4 groups 15-20, 21-25, 26-30, 31-35.
*	Displayed only top 20 cuisines in terms of count of users.
*	Filtered all null and blank ratings.

<h3>Analysis with Visualization</h3>

Analysis 1 : stacked bar chart to know who are the frequent customers with the combination of marital status , occupation and age.

![image](https://github.com/user-attachments/assets/0c5c426d-9be6-4655-a0e3-8444b2882be3)

*	The majority of users placing orders are in the 21-30 age range.
*	Single individuals are more likely to place orders compared to married individuals, especially in the 21-25 age group, because they might not know how to cook or there might me a time constraint to balance both.
*	Students and employed individuals are the predominant occupation categories among the users, because they might be staying alone at home and might not cook daily.
*	This analysis suggests that marketing and promotional efforts should be targeted primarily towards single individuals, particularly those who are students or employed, within the age group of 21-30, because for them it’s a need to order food for their daily basis. So, we should make them loyal toward Zomato for not shifting to other apps.

Analysis 2: A combination chart to show the correlation between amount spent on their purchase and their income, and find average amount spent per order.

![image](https://github.com/user-attachments/assets/bb22c5b1-a152-4424-96b2-229c8542e83c)

*	The count of users across all income categories shows a similar trend in both years, with slight variations.
*	The average sales figures remain relatively stable across the years, with minor increases or decreases in specific categories.
*	Users with no income or below Rs. 10,000 form the largest groups, suggesting that a significant portion of the user base falls within these categories.
*	Despite lower income, users below Rs. 10,000 show higher average sales amounts, indicating strong purchasing behavior.
*	Higher income groups (more than Rs. 50,000) also show a higher average sales amount, but the count of users is significantly lower compared to lower-income groups.
*	The consistency in the average sales amount over the years suggests stable purchasing behavior across different income groups.

  Analysis 3: line chart to find order pattern, which weekday there are more number of orders, for this create a new column to find the weekday from order date column from orders.

  ![image](https://github.com/user-attachments/assets/16816fbb-ae31-4a2c-9d10-81db7b2c8312)

*	General Trend: The overall trend shows that the count of users (and thus orders) increases as the week progresses, peaking towards the end of the week, particularly on Thursday and Friday. There is a noticeable drop during the weekend, especially on Sunday.
*	Family Size: The lines represent different family sizes, with each line depicting the order trends for that specific family size. The darker lines indicate larger family sizes, while the lighter lines represent smaller family sizes.
*	Order Volume: Larger family sizes consistently have higher order volumes compared to smaller family sizes. This is evident from the higher position of the darker lines on the graph.
*	Weekday Peaks: Orders peak significantly on Thursday and Friday across all family sizes. This suggests that users, regardless of family size, are more likely to place orders towards the end of the workweek to get relaxed for the weekend or might be tired working the whole week.
*	Weekend Decline: There is a sharp decline in orders on Saturday and Sunday. This could indicate that users prefer to order during the weekdays, possibly due to routine schedules or availability of products/services, might also visit restaurant directly for a weekend getaway.
*	Consistent Patterns: The patterns are consistent across different family sizes, indicating similar ordering behaviors regardless of the number of family members

Analysis 4: Bar chart for preference analysis which determines popular cuisine among different customer segments.

![image](https://github.com/user-attachments/assets/62c8136a-bcc0-4193-83a3-24025c63ec24)

*	Married users exhibit a more evenly distributed preference across different cuisines, while single users have more concentrated preferences, particularly for North Indian cuisine.
*	The popularity of Indian cuisines (North Indian, South Indian) among both segments suggests a strong cultural preference, possibly influenced by the demographic region.

Analysis 5: Highlighted table to show the rating of restaurants and number of orders for each restaurant.

![image](https://github.com/user-attachments/assets/91245103-89c5-4c1a-84b8-cdcb2a8e9163)

* Most restaurants received a majority of ratings of 3 or 4, indicating generally favorable but not exceptional feedback.
*	Baskin Robbins, Subway, McDonald’s, and LunchBox show similar patterns, with higher counts in the 3 and 4 rating groups.
*	A few restaurants received significant counts of lower ratings (1 and 2), such as Domino’s Pizza and One Story Pizza. This indicates some dissatisfaction among a subset of users.
*	The distribution of ratings highlights that users are generally satisfied but not overwhelmingly impressed, as evidenced by the lack of any restaurant achieving a 5-star rating.
*	Very few restaurants are rated at 5 but the number of reviews are very less like less than 30 where as the majority of reviews are of around three hundreds.
*	So according to my analysis people prefer the number of reviews than the most rated restaurant. 

Analysis 6: Bar chart to determine different order sizes i.e sales quantity across different customer segments. 

![image](https://github.com/user-attachments/assets/47043ba0-e3aa-4982-9e4f-e3f75323d633)

*	The data suggests that single-member families tend to purchase more on average than families of other sizes.
*	For family sizes 3 through 6, the purchasing behavior is quite similar, indicating that the average sales quantity is consistent across these family sizes.
*	The slight increase in average sales quantity for family size group 2 might indicate a transitional purchasing behavior as family size increases from 1 to 2.

<h3>Recommendations</h3>

*	Marketing and promotional efforts should be targeted primarily towards single individuals, particularly those who are students or employed within the age group of 21-30.
*	Marketing strategies could be tailored to engage users with no income and below Rs. 10,000, as they form a substantial portion of the user base with strong purchasing power.
*	Mid-Week Promotions: Since orders peak towards the end of the week, introduce mid-week promotions to boost sales on Monday, Tuesday, and Wednesday. Discounts, special offers, or limited-time deals can help increase order volume during these days.
*	Family Size Segmentation: Tailor marketing messages based on family size. Larger families may respond well to bulk purchase discounts, while smaller families might prefer single-item discounts or combo offers.
*	Staffing: Align staffing levels with peak order times to ensure efficient handling of orders and customer service. Increase staff during high-demand days and reduce during low-demand periods.
*	Ensure the menu features the top cuisines prominently and consider expanding offerings in North Indian and Chinese categories to meet demand.
*	Encourage users to provide feedback by offering incentives such as discounts or loyalty points for detailed reviews and ratings. This can help gather more actionable insights and make the other customer easy to decide on their purchase with reviews and ratings.
*	Use email marketing, social media, and in-app notifications to communicate promotions, new products, and loyalty programs to your customers.

<h3>Conclusion</h3>

Target Single Individuals: Focus on single-member families, especially those aged 21-30, as they show higher average sales quantities. Income-Based Targeting: Engage users with no income or below Rs. 10,000 and attract higher-income users (above Rs. 50,000) to boost sales. Mid-Week Promotions: Introduce special offers from Monday to Wednesday to balance order volumes throughout the week. Family Size Segmentation: Tailor marketing messages and offers based on family size to increase relevance and appeal. Operational Efficiency: Align staffing with peak order times and use automated order reminders to enhance customer service and capture more sales. Implementing these strategies can effectively enhance user engagement, increase sales, and improve overall customer satisfaction.

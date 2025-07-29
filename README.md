# E-commerce Platform Optimization: Mobile App vs Website

### Project Overview

This project was completed for a New York-based E-commerce company that specializes in selling clothing online. In addition to their digital storefront, the company offers in-store style and clothing advisory sessions, providing customers with a personalized shopping experience.

The company is currently at a strategic crossroads and needs to decide where to focus future development efforts: on enhancing their mobile app experience or improving their website. To support this decision, I conducted a data-driven analysis using Linear Regression to identify which platform contributes more significantly to key business metrics such as sales, Yearly Amount Spent, and Length of Membership.

### Objectives
•	Analyze customer interaction data across both the mobile app and website.

•	Determine the relationship between platform usage and Yearly Amount Spent.

•	Provide actionable insights into which platform yields higher Yearly Amount Spent and should be prioritized for development.

### Methodology
#### • Data Collection: Historical customer data was gathered, including:
•	Average Number of sessions (mobile app vs website)

•	Yearly Amount Spent per platform

### •	Modeling Approach:
•	Applied Linear Regression to quantify the impact of mobile and web usage on the Yearly Amount Spent.

•	Evaluated model performance using metrics such as Mean Absolute Error, Mean squared Error  and Root Mean Square Error.

•	Interpreted coefficients to determine which platform had a stronger influence on Yearly Amount Spent.

### Results Based on Coefficients
1.	Avg. Session Length (25.98)
For each additional unit increase in average session length, the predicted yearly amount spent increases by approximately $25.98, assuming other variables remain constant.

	2.	Time on App (38.59)
For every additional unit of time spent on the mobile app, the predicted yearly spending increases by around $38.59, holding other factors constant.
This is a strong positive relationship, indicating the app experience is likely driving revenue.

	4.	Time on Website (0.19)
For each additional unit of time spent on the website, yearly spending increases by only $0.19.
This is a very weak impact compared to the app.

	6.	Length of Membership (61.28)
For each additional unit (likely a year) of membership, the predicted yearly spending increases by about $61.28, which makes sense since loyal customers tend to spend more over time

### Recommendation

Based on the coefficients:
•	Time on App has a much higher positive impact on sales compared to Time on Website.

•	This strongly suggests that the company should focus more on enhancing the mobile app experience to drive revenue and customer engagement.

### Tools & Technologies
•	Python (Pandas, Scikit-learn, Matplotlib/Seaborn)

•	Jupyter Notebook

Project Overview
This project aims to analyze customer reviews of airline services to determine whether customers are likely to recommend the airline to others. The dataset includes various attributes such as airline name, type of aircraft, traveler type, seat type, and ratings of service during the flight, including an overall rating. The objective is to predict customer recommendations based on their reviews.

Data Preprocessing
The data preprocessing pipeline involves cleaning the data by handling missing values and dropping irrelevant columns. For text columns with few duplicates, dropping duplicates was sufficient. However, for the type of aircraft column, which had many duplicates and was deemed unnecessary, the entire column was dropped. Numerical columns were interpolated to replace missing values.

Data Exploration
Exploratory analysis revealed that most rows were similar, indicating correctly collected data and potential customer patterns. Ratings were normally distributed and scaled to improve accuracy, although this step may be optional in future iterations. Correlation matrices showed high positive correlations between features, suggesting that dissatisfaction with one aspect of the flight could indicate dissatisfaction with others. Furthermore, sentiment analysis indicated that customers were mostly dissatisfied if there was no inflight entertainment.

Recommendations
Display companies with high recommendations prominently in the app.
Collaborate more with highly recommended companies.
Consider increasing markup for top recommended companies.
Prioritize companies with the best overall ratings but be cautious of outliers.
Utilize classification methods to predict customer recommendations with 96% accuracy.
Consider implementing a pricing strategy based on customer recommendations and differences between flights.
Conclusion
This project presents a win-win strategy to increase profitability and customer satisfaction by leveraging machine learning to predict customer recommendations. By prioritizing recommended airlines, collaborating with them, and adjusting markup accordingly, the company can enhance customer experience and profitability simultaneously. Overall, implementing these recommendations could significantly increase value for both customers and the company. Adjustments and further refinements may be necessary based on future iterations and feedback.

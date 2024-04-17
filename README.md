# Customer Satisfaction Analytics Project

## Project Overview
The project aims to analyze customer satisfaction data to provide valuable insights and recommendations for the company. The project covers the following key aspects:

1. **Overview of Customer Satisfaction**: Discusses the significance of evaluating customer satisfaction and how it helps businesses identify areas for improvement and enhance the customer experience.

2. **Analyzing Customer Satisfaction**: Explains how analyzing customer satisfaction data provides insights into customer perceptions and sentiments, enabling data-driven decision-making to improve customer satisfaction and loyalty.

3. **Dataset Overview**: Provides details about the dataset, including the number of columns and rows, as well as the key attributes and their meanings.

4. **Data Retrieval and Transformation**: Describes the process of connecting to the database, examining the data structure, and performing data cleaning and transformation using Power Query in Power BI.

5. **Visualizations and Insights**: Presents various visualizations in Power BI, including:
   - Distribution of call channels
   - Customer response time analysis
   - Customer sentiment analysis by reason for contact
   - Customer call trends by day
   - Geographical distribution of calls by state
   - Key influencers of customer sentiment
   - Customer interactions by channel and reason
   - Customer sentiment by channel
   
[Click Here For Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiODdkNzA0OTItZjEyZC00ZDY1LWJiNTQtMzMxNGEzMDYzM2Y4IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)

6. **Insights and Analysis**: Summarizes the key patterns, trends, and interpretations derived from the visualizations, covering areas such as channel dynamics, response time efficiency, and sentiment analysis.

7. **Conclusion and Recommendations**: Provides a summary of the findings and offers recommendations for the company, including:
   - Diversifying channel strategies to cater to varied customer preferences
   - Optimizing service quality and addressing instances falling below SLA expectations
   - Strategically allocating resources based on insights from weekday engagement and geographic distribution
   - Addressing challenges in the Call-Center and enhancing the online experience

## Methodology
The project utilized the following methodologies:

1. **Data Retrieval**: Established a connection to the provided MySQL database using MySQL Workbench and Power BI.
2. **Data Cleaning and Transformation**: Performed data cleaning and transformation tasks in Power Query, such as handling imbalances in the `csat_score` column and adjusting the `call_timestamp` format.
3. **Visualization and Analysis**: Leveraged Power BI to create various visualizations, including charts, maps, and the Key Influencers feature, to uncover insights and patterns in the data.
4. **Interpretation and Recommendations**: Analyzed the visualizations and insights to identify key patterns, trends, and opportunities for improvement. Provided recommendations for the company based on the findings.

## Key Findings and Insights
The analysis of the customer satisfaction data revealed the following key findings and insights:

1. **Channel Dynamics**: The Call-Center dominates customer interactions, emphasizing a preference for personalized service. Chatbots and the Web channel show potential for growth and improvement.
2. **Response Time Efficiency**: The company excels in responding within SLA times, but opportunities exist to reduce instances falling below SLA and enhance overall service quality.
3. **Sentiment Analysis**: The Call-Center exhibits a mix of positive and negative sentiments, suggesting areas for improvement. The Web channel stands out with low Very Negative sentiments, indicating positive customer experiences.
4. **Behavioral Insights**: Customer activity peaks towards the end of the week, suggesting opportunities for targeted marketing efforts. The geographic analysis provides insights for strategic decisions in marketing and customer service.

## Recommendations
Based on the findings and insights, the following recommendations are provided for the company:

1. **Diversify Channel Strategies**: While the Call-Center is prominent, consider diversifying channel strategies to cater to varied customer preferences. Enhance online channels like Chatbot and Email to provide comprehensive support options.
2. **Optimize Service Quality**: Focus on refining service quality, especially in instances falling below SLA expectations. Implement measures to ensure a consistent and efficient response across all customer interactions.
3. **Strategic Resource Allocation**: Utilize insights from weekday engagement and geographic distribution to strategically allocate resources. Concentrate marketing efforts in states with high customer presence, aligning with the company's strategic goals.
4. **Address Call-Center Challenges**: Given the elevated negative sentiments in the Call-Center, prioritize targeted efforts in training and quality assurance. Identify pain points and implement solutions to enhance the overall customer experience.
5. **Enhance Online Experience**: Leverage opportunities to improve the Chatbot, Email, and Web channels. Prioritize initiatives to make these channels more user-friendly, engaging, and effective in positively influencing customer sentiments.

By implementing these recommendations, the company can enhance its customer satisfaction, improve service quality, and optimize resource allocation to better meet the needs and preferences of its customers.

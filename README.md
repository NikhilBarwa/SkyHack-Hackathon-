Skyhack 2024 - Call Center Optimization for United Airlines
Project Description
This project was created for the Skyhack 2024 Hackathon, where the challenge was presented by United Airlines. The focus was on optimizing call center operations by improving key performance metrics like Average Handle Time (AHT) and Average Speed to Answer (AST). We utilized real-world call center data to identify inefficiencies and opportunities for improvement, with a particular emphasis on customer sentiment and the reasons for calls.

Our approach combined data analytics, machine learning, and visualization to deliver actionable insights for reducing call volume and improving service quality through better integration with the Interactive Voice Response (IVR) system.

Objective
Optimize call center operations by analyzing and improving key metrics such as:
Average Handle Time (AHT)
Average Speed to Answer (AST)
Identify common customer call reasons and suggest improvements for IVR integration.
Explore the relationship between call metrics and customer sentiment to enhance customer satisfaction and operational efficiency.
Data Sources and Processing
We worked with two primary datasets:

Calls Data: Contained information on call durations, timestamps (call start, end, and agent assignment), and other critical data points. The file also included call transcripts, which were vital for extracting insights about customer concerns and the nature of their queries.
Sentiment Analysis Data: Provided sentiment scores based on the tone of both the customer and agent during calls, which helped us to identify the emotional context of the interactions.
Data Cleaning and Preprocessing
Converted date-time fields (call start, agent assignment, and call end) to ensure consistent formats.
Calculated key metrics such as:
Handle Time: The difference between call_end_datetime and agent_assigned_datetime.
Waiting Time: The difference between agent_assigned_datetime and call_start_datetime.
Handled missing or incorrect date formats and identified potential inconsistencies.
Performed text analysis on call transcripts to find patterns in call reasons.
Key Analyses and Findings
Average Handle Time (AHT) and Sentiment Analysis:

A boxplot was created to visualize the distribution of AHT across different customer sentiment levels. We observed that calls with more negative sentiments tended to have longer handle times, indicating that dissatisfied customers require more attention and time.

Average Speed to Answer (AST) and Sentiment Analysis:

Similar to AHT, a boxplot was generated for AST, showing that calls with lower sentiment were often answered more slowly, highlighting potential stress points in the call handling process.

Frequent Call Reasons:

Using text analysis techniques, we identified the most common reasons for calls, such as "flight return details" and "booking issues". These patterns provide insights for IVR optimization, as certain repetitive queries could be handled by automated systems rather than human agents.
Cluster Analysis:

A Principal Component Analysis (PCA) was performed to reduce dimensionality and group calls into clusters based on call reason, sentiment, and handle time. This allowed us to identify patterns and outliers in the data that could be used to improve call handling efficiency.

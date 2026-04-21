
### **Project Overview**:

The **Customer Support Ticket Analyzer** is a Python-based data analytics project designed to transform raw customer support data into actionable business insights. By analyzing ticket descriptions and priority levels, the project identifies common service bottlenecks, gauges customer sentiment, and suggests strategies to improve overall service quality.

**Key Features:**

* **Keyword Sentiment Tracking**: Monitors the frequency of specific sentiment-driven keywords such as 'good', 'poor', 'slow', and 'excellent' to measure customer satisfaction.
* **Priority Distribution Analysis**: Provides a count-based breakdown of ticket priorities (High, Medium, and Low) to help teams understand workload distribution.
* **Diagnostic Length Analysis**: Identifies complex issues by extracting the ticket with the longest word count, as longer descriptions often correlate with technical dissatisfaction.

**Analytical Framework:**

The project applies four levels of data analytics
1.  **Descriptive**: Identifies what happened by analyzing the mix of ticket priorities and recurring service themes.
2.  **Diagnostic**: Explains why issues occur, linking negative sentiment to response delays and complex technical problems.
3. **Predictive**: Forecasts that continued slow response times may lead to increased customer churn and more high-priority tickets.
4. **Prescriptive**: Recommends implementing Service Level Agreements (SLAs) and assigning experienced agents to high-priority, complex tasks.

**Dataset Description:**

The analysis is performed on a structured dataset containing the following attributes.
* **Ticket No**: Unique identifier for the support request.
* **Customer Name**: The name of the client reporting the issue.
* **Issue Description**: The raw text provided by the customer regarding their problem.
* **Priority**: The urgency level assigned to the ticket.

**Technologies Used:**

* **Python**: Core programming language for data processing.
* **Jupyter Notebook**: For interactive coding and visualization.
* **Data Structures**: Utilization of Python dictionaries and sets for efficient data management.



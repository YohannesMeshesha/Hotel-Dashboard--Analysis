# Hotel-Dashboard--Analysis


Introduction:
Data analysis plays a vital role in the hotel industry. Understanding hotel performance metrics is essential to making informed decisions and improving business operations. In this analysis, we will discuss the Hotel dashboard, which provides a comprehensive view of the hotel's performance by highlighting key losses and providing insights into the trends behind them.

Data Extraction and Transformation:
The Hotel dashboard data is extracted from an Excel file containing information on room bookings, cancellations, and revenue. The data undergoes several transformations to clean and prepare it for analysis, such as removing null values and duplicates. Additionally, a new calendar table is created to support time-based analysis, which categorizes dates by month, year, and day of the week.

![Dash](https://user-images.githubusercontent.com/131899006/236867459-59e12b1c-f2b5-4b9d-996a-6d56bd3d0545.png)


KPI Card:
The KPI card displays four essential metrics for analyzing a hotel's performance: Total revenue, Revenue loss, Average Daily Rate (ADR), and Total guests. The revenue loss is highlighted in red to indicate that it is a critical metric that needs attention.

Stacked Column Chart:
The stacked column chart shows the revenue loss and total revenue by month, with revenue loss highlighted in red to show the key losses. This chart helps identify the months with the highest revenue loss and the reasons behind it.

Line Stacked Column Chart:
The line stacked column chart displays the ADR and %Cancellations by month. The ADR is displayed as a line chart, while the %Cancellations is displayed as a stacked column chart, with cancellations highlighted in red to show the key losses. This chart helps identify the months with the highest cancellation rates and their impact on ADR.

Stacked Column Chart (Transformed):
This stacked column chart shows the %Cancellations by lead time transformed into four categories: Less than 7 days, 7-14 days, 14-30 days, and more than 30 days. The cancellations are highlighted in red to show the key losses. This chart helps identify the cancellation trends by lead time and their impact on revenue.

Clustered Bar Chart:
The clustered bar chart displays the total cancellations by weekdays, with cancellations highlighted in red to show the key losses. This chart helps identify the weekdays with the highest cancellation rates and the reasons behind it.

Stacked Column Chart (Transformed):
This stacked column chart displays the ADR by lead time transformed into the same four categories as before: Less than 7 days, 7-14 days, 14-30 days, and more than 30 days. This chart helps identify the ADR trends by lead time and their impact on revenue.

Conclusion:
In conclusion, the Hotel dashboard provides accurate and reliable data for decision-making and analysis by performing ETL and data cleaning. The dashboard highlights key losses in red and provides insights into the trends behind them, helping hotel managers identify areas of improvement and take corrective actions to optimize their revenue and ADR.

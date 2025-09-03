AI-Powered Sales Forecasting Dashboard
This project is an end-to-end Data Science and Business Intelligence solution built to predict future sales trends for a retail business. It involves data cleaning, feature engineering, time series forecasting using Facebook Prophet, and building an interactive dashboard in Power BI for visualization and decision-making.

Completed as Task 1 of the Future Interns real-world internship program.

✨ Features
** Predictive Analytics:** Forecasts future sales using historical transaction data.

Interactive Dashboard: A Power BI dashboard with filters for category, region, and time periods.

Trend Analysis: Visualizes overall sales trends, yearly seasonality (e.g., holiday spikes), and weekly patterns.

Actionable Insights: Provides clear business recommendations based on the forecasted data.

🛠 Tech Stack
Programming Language: Python

Libraries: Pandas, Facebook Prophet, Matplotlib

Visualization Tool: Power BI Desktop

Environment: Google Colab / Jupyter Notebook

📁 Project Structure
text
AI-Sales-Forecast/
│
├── data/
│   └── sample_superstore.csv    # Raw dataset
│
├── notebooks/
│   └── Sales_Forecasting_Analysis.ipynb  # Jupyter notebook for data cleaning & model training
│
├── outputs/
│   ├── sales_forecast_for_power_bi.csv   # Processed data for Power BI
│   └── forecast_plots.png                # Sample output plots
│
├── dashboard/
│   └── Sales_Forecast_Dashboard.pbix     # Interactive Power BI dashboard file
│
└── README.md
🚀 How to Run This Project
1. Data Preparation and Model Training
Clone the repository:


git clone https://github.com/your-username/AI-Sales-Forecast.git
cd AI-Sales-Forecast
Open the Jupyter Notebook:

jupyter notebook notebooks/Sales_Forecasting_Analysis.ipynb
Or run it directly on Google Colab.

Run the cells sequentially to:

Install dependencies (pandas, prophet).

Load and clean the data.

Aggregate daily sales.

Train the Facebook Prophet model.

Generate future forecasts.

Export the results to a CSV file for Power BI.

2. Visualize in Power BI
Open Power BI Desktop.

Load the generated sales_forecast_for_power_bi.csv file from the outputs/ folder.

Open the provided Sales_Forecast_Dashboard.pbix file or build your own dashboard by:

Using ds as the date axis.

Plotting Actual_Sales and Forecasted_Sales on a line chart.

Adding slicers for interactivity.

📊 Key Insights from the Forecast
The model identified a consistent yearly seasonality with a significant sales peak during the November-December holiday period.

An overall upward trend in sales was observed over the years.

Recommendations include increasing inventory and marketing efforts before Q4 to capitalize on forecasted high demand.

🔮 Future Enhancements
Incorporate external variables like marketing spend and holidays.

Deploy the model as an API for real-time forecasting.

Automate the data pipeline with AWS SageMaker or Azure ML.

👨‍💻 Author
Rercharla Pavan Chowdhary

LinkedIn: https://www.linkedin.com/in/pavan-chowdary-764b64324/

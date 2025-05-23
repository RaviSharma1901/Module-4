# Hotel Bookings Power BI Dashboard
### Project Overview

This project contains a comprehensive Power BI dashboard analyzing hotel booking data.
The dashboard transforms exploratory data analysis (EDA) findings into interactive visualizations to
provide insights into hotel booking patterns, customer behavior, and business performance metrics.

__Project Structure__
├── Hotel Bookings.xlsx                    # Original raw dataset    
├── hotel_bookings_cleaned.xlsx           # Cleaned and processed dataset    
├── Hotel_Booking_Dashboard.pbix          # Power BI dashboard file      
├── Screenshot 2025-01-29 124711.png      # Dashboard preview/screenshot    
└── The_DataViz_Challenge_Transforming_EDA_Projects_to_Dashboards.ipynb  # Jupyter notebook with EDA    

__Technologies Used__
- **Power BI Desktop**: Dashboard creation and data visualization    
- **Microsoft Excel**: Data storage and preprocessing      
- **Python/Jupyter Notebook**: Exploratory data analysis and data cleaning    
- **Pandas**: Data manipulation and analysis      

__Prerequisites__
- To view and interact with this dashboard, you'll need:
- Power BI Desktop (latest version recommended)
- Microsoft Excel (for viewing raw data files)
- Python 3.x with Jupyter Notebook (optional, for EDA review)

__Getting Started__
1. Opening the Dashboard   
- Download and install Power BI Desktop if you haven't already
- Clone or download this repository
- Open Hotel_Booking_Dashboard.pbix in Power BI Desktop
- If prompted, ensure data connections point to the correct file paths

2. Data Sources
- The dashboard uses the following data files:
      - Primary Dataset: hotel_bookings_cleaned.xlsx - Contains the processed and cleaned hotel booking data
      - Original Dataset: Hotel Bookings.xlsx - Raw dataset for reference

3. Refreshing Data
- If you need to update the data:
      - Replace the Excel files with your updated datasets
      - In Power BI, go to Home > Refresh
      - Resolve any data source path issues if they arise

__Dashboard Features__      
- The Power BI dashboard includes visualizations and insights covering:      
       - Booking Trends: Seasonal patterns and booking volumes over time      
       - Customer Segmentation: Analysis of different customer types and their booking behavior      
       - Hotel Performance: Occupancy rates, revenue metrics, and operational insights      
       - Geographic Analysis: Booking patterns by location/country      
       - Cancellation Analysis: Understanding booking cancellations and their impact      
       - Interactive Filters: Dynamic filtering capabilities for detailed analysis      

__Key Metrics Tracked__            
       - Total bookings and revenue      
       - Average daily rate (ADR)            
       - Occupancy rates      
       - Cancellation rates      
       - Lead time analysis      
       - Customer demographic insights      
       - Seasonal booking patterns      

__Exploratory Data Analysis__      
- The The_DataViz_Challenge_Transforming_EDA_Projects_to_Dashboards.ipynb notebook contains:      
       - Data cleaning processes      
       - Statistical analysis      
       - Initial data exploration findings      
       - Preparation steps for dashboard creation      
- To view the EDA notebook:      

      jupyter notebook The_DataViz_Challenge_Transforming_EDA_Projects_to_Dashboards.ipynb

__Use Cases__
- This dashboard is ideal for:
       - Hotel Managers: Understanding booking patterns and optimizing operations
        - Revenue Analysts: Analyzing pricing strategies and revenue optimization
        - Marketing Teams: Identifying customer segments and seasonal trends
        - Data Analysts: Learning dashboard development from EDA projects
        - Students/Researchers: Understanding hospitality industry data analysis

__Dashboard Preview__

![Dashboard Preview](https://github.com/RaviSharma1901/Module-4/blob/main/End%20Assessment/Screenshot%202025-01-29%20124711.png)

__Customization__

- To customize the dashboard for your needs:
        - Update data sources with your hotel booking data
        - Modify visualizations in Power BI Desktop
        - Adjust filters and parameters as needed
        - Add new metrics or KPIs relevant to your analysis

__Data Dictionary__
- Key fields in the dataset include:
        - hotel: Type of hotel (Resort/City)
        - arrival_date: Check-in date information
        - stays_in_nights: Total nights stayed
        - adults/children/babies: Guest composition
        - country: Guest origin country
        - adr: Average daily rate
        - is_canceled: Cancellation status


__Learning Resources__
- AlmaBetter Data Science Program
- Power BI Learning Path
- Data Analysis with Python
- Hotel Industry Analytics Best Practices 


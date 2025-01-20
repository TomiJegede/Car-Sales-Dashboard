# Car Sales Dashboard - Tableau Project

This dynamic **Car Sales Dashboard** in Tableau provides a comprehensive analysis of car sales data. The dashboard uses **calculated fields** to present key insights into sales performance, trends, and growth metrics. These calculated fields ensure that the dashboard updates automatically with the latest dataset, providing real-time insights.

## Key Features & Calculated Fields:

### 1. **YTD Total Sales**
The **YTD Total Sales** metric sums up the total sales for the most recent year in the dataset. This field is designed to ensure that the most current data is always displayed, even as the dataset is updated.

### 2. **PYTD Total Sales**
The **PYTD Total Sales** metric calculates the total sales for the previous year, allowing for comparisons between the current and previous year's performance.

### 3. **Year-on-Year (YoY) Growth**
The **YoY Growth** metric measures the percentage change in sales from the previous year to the current year, providing insights into sales growth or decline.

### 4. **YTD Cars Sold**
The **YTD Cars Sold** field counts the number of cars sold in the most recent year, providing insight into the volume of sales.

### 5. **YTD Avg Price**
The **YTD Avg Price** is calculated by dividing the total sales for the year by the total number of cars sold, giving the average price per car for the most recent year.

### 6. **Custom Number Formatting**
The dashboard uses custom number formatting to display values clearly:
- YTD Total Sales is shown in millions with currency formatting.
- YTD Cars Sold is displayed in thousands with a simple numeric format.

## Visualizations:

The dashboard includes a variety of interactive visualizations to explore the data:

- **KPI Metrics:**
  - YTD Total Sales
  - YTD Avg Sales
  - YTD Cars Sold
  
- **Charts:**
  - Line chart for YTD Total Weekly Sales
  - Pie chart for YTD Sales by Body Style
  - Doughnut chart for YTD Sales by Color
  - Bar chart for YTD Cars Sold by Dealer Region

- **Table:**
  - A detailed table displaying **Sales Trends by Car Brand-Company**, including metrics like YTD Cars Sold, YTD Avg Sales, YTD Total Sales, and % of YTD Total Sales.

## Filters:
The dashboard includes interactive filters to drill down into the data by:
- **Date**
- **Transmission**
- **Body Style**
- **Engine**
- **Gender**

## Design & Customization:

### Background:
The dashboard features a custom background designed in PowerPoint, which was saved as a JPEG and added to Tableau to create a visually appealing and branded layout.

### Dual-Axis Charts:
A dual-axis chart is used to display both an area chart and a line chart. The axes are synchronized, with each chart type representing different data points on the same axis.

### Date Range Calculation:
The **MIN** and **MAX** date calculations ensure that the dashboard always reflects the full range of available data, automatically updating when the dataset changes.

## Real-Time Data Updates:
The use of calculated fields and dynamic filters ensures that the dashboard updates automatically to reflect the latest available data, providing users with real-time insights.

**Dashboard Link:** [Car Sales Insight Dashboard](https://public.tableau.com/app/profile/tomi.jegede/viz/CarSalesInsight_17367960164050/Dashboard?publish=yes)

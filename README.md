# Amazon Sales Analysis Project

A comprehensive data analysis project examining Amazon sales patterns, profitability, and regional performance using Python analytics and Power BI visualizations. This project provides actionable insights into sales trends, product performance, and market dynamics.

## Project Overview

The analysis explores key aspects of Amazon's sales data:
- Regional sales and profit analysis
- Product category performance
- Monthly revenue trends
- Order priority patterns
- Units sold vs. profitability relationships

## Features

### Python Analysis Components
1. Regional Performance Analysis
   - Total profit by region visualization
   - Regional revenue comparisons
   - Cost structure analysis

2. Product Category Analysis
   - Revenue distribution across categories
   - Product performance metrics
   - Category profitability analysis

3. Time Series Analysis
   - Monthly revenue trends
   - Seasonal pattern identification
   - Year-over-year comparisons

4. Order Analytics
   - Priority distribution charts
   - Units sold correlation studies
   - Regional ordering patterns

### Power BI Dashboards

1. Sales Overview Dashboard
   - KPI cards (Revenue, Profit, Units Sold)
   - Trend indicators
   - Regional performance heatmap
   - Top/bottom performing products

2. Product Analysis Dashboard
   - Category-wise performance
   - Product profitability matrix
   - Inventory analysis
   - Seasonal product trends

3. Regional Intelligence Dashboard
   - Geographic sales distribution
   - Regional profit margins
   - Market penetration metrics
   - Regional comparison cards

## Requirements

```python
pandas>=1.0.0
matplotlib>=3.2.0
seaborn>=0.10.0
```

Additional Requirements:
- Power BI Desktop (Latest version)
- Power BI Pro/Premium for sharing

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Adnan1902/Amazon_Sales_Data_Analysis_Project.git
cd amazon-sales-analysis
```

2. Create and activate virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
```

3. Configure Power BI:
   - Install Power BI Desktop
   - Open amazon_sales_dashboard.pbix
   - Set up data source connections

## Usage

### Running Python Analysis
```bash
python sales_analysis.py
```

This will generate:
- Regional profit visualizations
- Product category analysis
- Time series trends
- Order priority charts
- Units sold correlation plots

### Navigating Power BI Dashboard

1. Sales Overview:
   - View KPIs and main metrics
   - Filter by time period
   - Analyze regional performance
   - Track product performance

2. Product Analysis:
   - Explore category performance
   - Analyze product profitability
   - Track inventory metrics
   - Identify seasonal trends

3. Regional Analysis:
   - Examine geographic distribution
   - Compare regional performance
   - Analyze market penetration
   - Track regional profitability

## Project Structure

```
amazon-sales-analysis/
│
├── data/
│   └── Amazon Sales data.csv
│
├── scripts/
│   └── sales_analysis.py
│
├── visualizations/
│   ├── python_viz/
│   │   ├── regional_profit.png
│   │   ├── product_revenue.png
│   │   ├── monthly_trend.png
│   │   ├── order_priority.png
│   │   └── profit_correlation.png
│   │
│   └── power_bi/
│       └── amazon_sales_dashboard.pbix
│
├── requirements.txt
└── README.md
```

## Key Insights

1. Regional Performance
   - Detailed profit distribution by region
   - High-performing market identification
   - Regional cost structure analysis

2. Product Performance
   - Top revenue-generating categories
   - Product profitability analysis
   - Category growth trends

3. Sales Patterns
   - Monthly revenue fluctuations
   - Seasonal trends identification
   - Order priority impact

4. Business Metrics
   - Units sold vs. profit correlation
   - Regional efficiency comparisons
   - Priority order distribution

## Future Enhancements

1. Analytics Expansion
   - Predictive sales forecasting
   - Customer segmentation
   - Product recommendation system
   - Inventory optimization

2. Dashboard Improvements
   - Real-time data integration
   - Advanced filtering options
   - Custom reporting templates
   - Mobile optimization

3. Automation Features
   - Automated data refresh
   - Scheduled report generation
   - Email notifications
   - API integration

## Contributing

To contribute to this project:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingSalesFeature`)
3. Commit your changes (`git commit -m 'Add sales feature'`)
4. Push to the branch (`git push origin feature/AmazingSalesFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Amazon for the sales dataset
- Python data analysis community
- Power BI development team

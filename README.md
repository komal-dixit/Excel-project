 # Sales and Financial Analysis for AtliQ Hardware

## **Project Overview**

AtliQ Hardware is a global company selling products like printers, mice, PCs, and more. These products are sold to two primary customer types: online retailers such as Amazon and Flipkart, and physical stores like Croma and Best Buy. The company operates through three sales channels:

- **Retailer**: Croma, Amazon
- **Distributor**: Neptune
- **Direct**: AtliQ eStore, AtliQ Exclusive

## **Project Objective**

The main purpose of this analysis is to assess the sales and financial performance of AtliQ Hardware from 2019 to 2021. The findings from this analysis will aid in data-driven decision-making, sales trend identification, and market performance evaluation. AtliQ's fiscal year runs from September to August.

## **Key Goals**

### **Enabling Strategic Decisions**

- **Monitor and assess** sales operations and performance.
- **Detect sales trends** and key performance indicators (KPIs).
- **Assess discount strategies**, improve negotiation power, and explore market expansion possibilities.

### **Evaluating Financial Health**

- **Provide insights** to facilitate decision-making and stakeholder communication.
- **Compare performance** with industry benchmarks and previous years.
- **Establish a framework** for budgeting and forecasting.
- **Align financial planning** with strategic goals and boost confidence in the company’s outlook.

## **Reports Generated**

- **Customer Net Sales Analysis**
- **Market/Country Performance vs. Targets**
- **Top 10 Products by Sales**
- **Top 5 and Bottom 5 Products by Quantity Sold**
- **Sales by Division**
- **New Products Launched in 2021**
- **Top 5 Countries/Marketplaces by Sales in 2021**
- **Profit and Loss (P&L) Reports by Fiscal Years**
- **P&L Reports by Month**

## **Methods Employed**

### **ETL Process (Extract, Transform, Load)**

Using Power Query Editor, data was extracted, cleaned, and transformed from various sources to ensure accuracy and consistency. This process included:

- Generating proper headers
- Handling inconsistent values
- Converting negative values in the 'Qty' column into absolute values

### **Date Table Generation**

A Date Table was created in Power Query to generate unique dates essential for analysis.

### **Fiscal Period Derivation**

Using Power Pivot, fiscal months and quarters were accurately defined in line with AtliQ Hardware’s fiscal calendar.

### **Data Modeling**

Relationships between fact and dimension tables were established using Power Pivot to enable detailed analytics.

### **Incorporating Additional Data**

Supplementary data was integrated into existing models using Power Pivot, expanding the depth of analysis.

### **DAX (Data Analysis Expressions)**

DAX formulas were used to create calculated columns that allowed for more dynamic and detailed reporting.

### **Pivot Tables**

Pivot Tables were utilized to develop comprehensive reports.

### **Conditional Formatting**

Key figures were highlighted using conditional formatting to ensure quick and clear insight extraction.

## **Observations & Insights**

### **Top 3 Customers (2021)**

- **Amazon**: $82.1M
- **AtliQ Exclusive**: $61.1M
- **AtliQ eStore**: $53.0M

### **Market Growth**

- All markets showed growth in 2021, with India and the USA leading. However, sales targets were not fully met.

### **Top-Selling Product (2021)**

- The **'AQ Electron 4 3600 Desktop Processor'** generated the highest sales, totaling $19.4M.

### **Top and Bottom Products by Quantity**

- **Top**: **'AQ Master Wired x1 Ms'** with 4.2M units sold.
- **Bottom**: **'AQ HOME Allin1 Gen 2'** with 8.9K units sold.

### **Division Sales**

- **Peripherals & Accessories**: $338.4M
- **PCs**: $165.8M
- **Networking & Storage**: $94.7M

### **New Product Sales**

- 16 new products launched in 2021 contributed $176.2M, representing 29.4% of total sales.

### **Top 5 Countries/Marketplaces (2021)**

- **India**
- **USA**
- **South Korea**
- **Canada**
- **United Kingdom**

## **Profit & Loss (P&L) Insights**

### **By Fiscal Year**

- Net sales showed significant growth from 2019 to 2021. However, the Cost of Goods Sold (COGS) increased at a faster rate, leading to a slight decline in the gross margin percentage (GM%).

### **By Country/Market**

- **Top markets** like India, the USA, and South Korea drove large sales volumes but with lower GM%, pointing to higher COGS. These markets should focus on cost-reduction strategies.
- Markets like **New Zealand, Japan**, and the **UK** were the most profitable in terms of GM%, suggesting strong pricing power or cost control.

### **By Month**

- Net sales surged by about 584.6% from 2019 to 2021. COGS also rose, resulting in a lower GM%. Peak sales were observed in October, November, and December across all years, indicating seasonality. Planning around these trends could improve performance during high-demand periods.

## **Skills Acquired**

- Developed an advanced understanding of business metrics and their impact on overall performance.
- Gained proficiency in designing intuitive and user-focused reports.
- Improved efficiency in report generation by streamlining processes for timely delivery.
- Acquired skills in building structured methodologies for consistent and impactful report generation.

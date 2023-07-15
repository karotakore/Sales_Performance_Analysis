# Sales Performance Analysis

## Background
    
In this analysis, I will explore the comprehensive dataset of *Deltoid Holdings*, a flourishing superstore, to gain insights and understanding. With the goal of enhancing customer patronage, streamlining processes, and boosting the bottom line, this report presents a thorough examination of the store's sales performance.
    
The data collection at hand encompasses a wealth of information, enabling us to gain valuable insights into customer orders, shipment dates for goods and services, and the specific regions to which the consumers belong. This expansive data provides a holistic view of the supermarket's operations, empowering us to conduct an in-depth analysis.
    
Segmentation plays a crucial role in understanding the diverse end users of the superstore's products. By categorizing market segments into areas such as 'corporate' and 'home office,' and examining their buying behavior, I gain a deeper understanding of the distinct customer groups, their preferences, and can tailor strategies to better cater to their unique needs.
    
Comprising 26 columns and approximately 10,000 rows, this dataset offers a rich tapestry of information, presenting ample opportunities for detailed analysis. As a data analyst, I will utilize Power BI as my tool of analysis and visualization to harness the power of this data, uncovering meaningful patterns, trends, and opportunities for improvement. The data will also be loaded into Pandas to perform exploratory data analysis.
    
Through this sales analysis, I aim to provide actionable insights that will drive decision-making, foster stronger customer relationships, optimize operational efficiency, and ultimately boost the superstore's profitability.
    
In conclusion, this sales report holds significant potential for driving customer engagement and boosting the overall profitability of *Deltoid Holdings*. Through meticulous analysis of the dataset's diverse information, I will uncover invaluable insights that will shape impactful business strategies and pave the way for long-term success.

## Exploratory Data Analysis 
This involves looking at the data summaries and visualizations to:
1.	Analyse the data
2.	Discover patterns and relationships between the features
3.	Identify the data types
4.	Clean up the data

### Loading the Dataset into Pandas
Initially, the data was read into the Python Environment using the pandas package, which provided me the functionality of viewing a description of the dataset. 

Below is a screenshot of the code used for loading the data into Python.

![Loading Data in Pandas](https://github.com/karotakore/Sales_Performance_Analysis/assets/116779227/7088505a-e7fc-47f9-8a45-2b483c90498a)
---

### Understanding the Data
This involved several processes such as:
1. Showing the data types
2. Descriptive statistics
3. Displaying the number of columns and rows.

### Data Cleaning

Perform a preliminary data inspection and data cleaning.

a. Check for missing data and formulate an apt strategy to treat them.

b. Remove duplicate data records.

### Establishing Strength of Association Between Variables
Computing the correlation matrix for the superstore dataset

![Correlation Matrix_Formula](https://github.com/karotakore/Sales_Performance_Analysis/assets/116779227/f5bccb49-227e-4a42-972c-dcfd7fd95e14)
---

With the aid of seaborn and matplotlib, I plotted a heatmap of the variables using the computed correlation matrix. This is to show the strength of association between the variables and also those that are strongly related.

It can be inferred that revenue and sales are strongly positively correlated, and there is a high association between sales and profit. Additionally, there is a negative relationship between discount and profit.

![Correlation_Matrix_Heatmap II](https://github.com/karotakore/Sales_Performance_Analysis/assets/116779227/6c76a789-f79f-45e4-82b2-a10e2594ff15)
---

### Selecting the Independent and Dependent Variables; Splitting the Data into Training and Test Sets

![Train and Test Sets](https://github.com/karotakore/Sales_Performance_Analysis/assets/116779227/39eeb11e-b4a9-4953-8534-5353ddc3ba53)
---

### Feature Importance
Here, I'll sort the features and their values in descending order. 

![Feature Importances](https://github.com/karotakore/Sales_Performance_Analysis/assets/116779227/7866cb69-11d9-4e56-82c6-fe89b9c4405d)
---

![Feature Importances_Bar Chart](https://github.com/karotakore/Sales_Performance_Analysis/assets/116779227/d44d000c-f12e-459e-976e-c29d89854fcb)
---

The transformed dataset was eventually saved to a csv file.

![Saving to csv](https://github.com/karotakore/Sales_Performance_Analysis/assets/116779227/f6bd4260-4d6f-493c-b694-4bb652868651)
---

### Visualization and Business Intelligence

![Sales Dashboard](https://github.com/karotakore/Sales_Performance_Analysis/assets/116779227/8e77b131-8574-44b7-a4ce-2ae5fe05f69c)
---

Notable findings and actionable insights include: 
1. The analysis reveals a strong negative correlation between discount levels and profitability. As the discount offered on products or services increases, the profit margin diminishes.

   The finding indicates that higher discount levels have a detrimental impact on profitability. It implies that the cost of providing discounts outweighs the potential revenue gained from increased sales.       It  is crucial for the business to carefully evaluate the trade-off between attracting customers through discounts and maintaining a healthy profit margin.

2. The finding that the sales figures declined by 2.83% from 2014 to 2015 while the profit and sales values are positively correlated provides an important business insight. It suggests that despite the          decline in sales, there is a positive relationship between profit and sales. 

   This indicates that higher sales volumes generally lead to higher profitability, even though there was a temporary setback in sales during this period.

### Recommendations
Based on these findings, the following strategies can be adopted:
1.	*Deltoid Holdings* can perform a thorough analysis to identify the discount thresholds at which profit margins significantly decline. Determine the optimal discount range that strikes a balance between customer attraction and profitability. Adjust discount levels accordingly to ensure that the business maintains a sustainable profit margin. 
       
2.	The superstore can also analyze customer segments to identify the most profitable and high-potential segments. Tailor marketing and sales strategies to cater specifically to these segments, leveraging personalized offers, targeted campaigns, and superior customer service to drive both sales and profitability.
    
### Conclusion
The sales analysis of *Deltoid Holdings* offers valuable insights into the performance and opportunities for growth. By thoroughly examining the sales data, we have uncovered significant findings that can guide strategic decision-making and drive business success.

Our analysis highlights the importance of continuously monitoring sales performance, customer preferences, and market dynamics. It is crucial for the superstore to adapt and refine its strategies based on these insights to remain competitive in a rapidly changing business environment.
    
This sales analysis serves as a foundation for future decision-making, enabling the superstore to make data-driven choices and align its efforts with market demands. By leveraging the insights gained from this analysis, the superstore can position itself for sustainable success in the dynamic retail landscape.    
    
In summary, this report provides actionable recommendations for the superstore. By capitalizing on the identified opportunities and aligning strategies with market trends, *Deltoid Holdings* can navigate challenges, drive growth, and enhance its position in the marketplace.







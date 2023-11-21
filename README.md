# Quantium-Virtual-Internship
**GitHub README Summary - Task 1: Data Analysis for Chip Purchasing Behavior**

**Objective:**
The goal of Task 1 was to analyze customer purchasing behavior for chips and derive meaningful insights to support a strategic recommendation for the upcoming category review. The analysis was performed using Python.

**Data Exploration and Cleaning:**
1. *Data Summary:* Conducted high-level data summaries to understand the dataset's structure, features, and general statistics.
2. *Outlier Detection:* Identified and removed outliers that could skew the analysis and impact the accuracy of insights.
3. *Data Format Check:* Ensured data integrity by examining and correcting data formats where necessary.

**Feature Engineering:**
1. *Pack Size and Brand Name:* Derived additional features such as pack size and brand name to provide a more comprehensive view of the dataset.

**Metric Definition:**
Defined key metrics to assess customer spending behavior:
1. *Total Spending:* Calculated total spending per customer to understand overall purchasing patterns.
2. *Purchase Frequency:* Examined how often customers make chip purchases.
3. *Brand Preference:* Explored which brands are favored by different customer segments.
4. *Pack Size Preference:* Analyzed the preference for specific pack sizes among customers.

**Customer Segmentation:**
Utilized metrics to identify and define distinct customer segments based on spending behavior. Segmentation allows for targeted insights into different customer groups.

**Commercial Insights:**
Linked insights to commercial applications, ensuring that recommendations are practical and impactful for the category manager, Julia. Considered how findings could influence marketing strategies, product placement, and promotional activities.

**Recommendation Preparation:**
Prepared the groundwork for a strategic recommendation to Julia, ensuring that the analysis results are well-supported by data and align with the overarching goal of the category review.

**Tools Used:**
Python was chosen for the analysis due to its versatility and extensive libraries for data manipulation and analysis, including pandas, numpy, and matplotlib.

**Next Steps:**
The insights derived from this analysis will serve as a foundation for the strategic recommendation in Task 2, where a more detailed and actionable plan will be formulated based on the identified customer segments and their purchasing behaviors.
**Task 2: Store Trial Performance Evaluation - Initial Findings**

**Objective:**
The objective of Task 2 is to evaluate the performance of a store trial conducted in stores 77, 86, and 88. The analysis focuses on comparing monthly sales metrics, including total sales revenue, total number of customers, and average number of transactions per customer, between each trial store and its selected control stores.

**Analysis Approach:**
1. **Monthly Sales Metrics:**
   - Calculated total sales revenue, total number of customers, and average transactions per customer for each store.
   - Analyzed the trends and patterns in the monthly sales data.

2. **Control Store Selection:**
   - Developed a function to compare different control stores to each trial store.
   - Used Pearson correlations or a magnitude distance metric to measure the similarity between each trial store and potential control stores.

3. **Comparative Analysis:**
   - Selected control stores for each trial store based on the developed function.
   - Compared each trial-control pair during the trial period.

4. **Hypothesis Testing:**
   - Tested if total sales are significantly different in the trial period compared to the control period.
   - Investigated the drivers of change, such as an increase in purchasing customers or purchases per customer.

**Code and Results:**
*Provided the initial findings and code in a PDF file.*

**Key Insights:**
1. *Control Store Selection:* Identified control stores that show a high level of similarity with each trial store, ensuring a meaningful comparison.
  
2. *Trial Period Analysis:* Observed variations in total sales during the trial period compared to the control period.
  
3. *Driver of Change:* Investigated the factors contributing to the observed changes, including an increase in the number of purchasing customers or purchases per customer.

**Next Steps:**
The initial findings serve as a foundation for a more in-depth analysis in Task 3. Further exploration will involve statistical testing to validate the observed differences and a deeper examination of the drivers behind the changes in sales metrics. Additional insights will be provided in the subsequent analysis to support informed decision-making regarding the store trial's effectiveness.

*Note: The code and detailed analysis are available in the attached PDF file.*

## -Projects
## Data Overview
The data set represents the financial and sales performance of a company over two fiscal years, 2015 and 2016. It includes the following key metrics:
1. Volumes:
   - This metric represents the total units or volume of goods sold by the company over the two-year period.
2. Gross Sales Discount:
   - This is the total value of discounts or promotions offered by the company to customers on their gross sales.
3. Discounts:
   - This is the total value of all discounts, including any additional discounts or allowances provided to customers.
4. Net Sales:
   - Net sales is calculated as the Gross Sales Discount minus the Discounts, representing the company's total revenue after accounting for various discounts and promotions.
5. Cost of Goods Sold:
   - This is the total cost incurred by the company to produce or acquire the goods that were sold.
6. Gross Profit:
   - Gross Profit is the difference between Net Sales and Cost of Goods Sold, representing the company's total profit before considering other operating expenses.
7. Distribution:
   - This is the cost associated with distributing or delivering the company's products to customers.

8. Warehousing:
   - The cost of storing and managing the company's inventory in warehouses.

9. Full Delivered Margin:
   - This metric represents the company's overall profitability, taking into account the costs of distribution and warehousing in addition to the Cost of Goods Sold.

The data set also includes two key performance indicators (KPIs):

1. Gross Profit %:
   - This is the Gross Profit as a percentage of Net Sales, indicating the company's profitability at the gross margin level.

2. FDM %:
   - This is the Full Delivered Margin as a percentage of Net Sales, providing a broader measure of the company's overall profitability.

The data is presented in a structured format, with columns for each metric and rows representing the values for 2015 and 2016. This allows for a comprehensive analysis of the company's financial and sales performance over the two-year period, enabling the identification of trends, changes, and areas for improvement.

# steps
- create the model
- create the pipeline (Pivot table)
- connect the pipeline using dynamic refrencing (= select the sum on the pivot table)
- add slicers
- built report


# Model built 

![Uploading FDM analysis.png…]()


#Report
FDM, Sales & Volume Analysis Report

Introduction:
This report provides a comprehensive analysis of the financial and sales performance of a company over two fiscal years, 2015 and 2016. The data includes key metrics such as volumes, gross sales discount, discounts, net sales, cost of goods sold, gross profit, distribution, warehousing, and full delivered margin, as well as key performance indicators (KPIs) like gross profit percentage and FDM percentage.

Problem Statement:
The analysis indicates that the company experienced a decline in its overall performance from 2015 to 2016, with decreases in volumes, net sales, gross profit, and key profitability metrics. This raises concerns about the company's financial health and the need to identify the root causes of the decline.

Methodology:
To gain deeper insights into the company's performance, the analysis leverages advanced pivot table techniques, including:
- Extracting data from columns with different data types
- Utilizing filtering and search options to focus on relevant information
- Handling data uniformity to ensure accurate analysis
- Calculating and interpreting variance and absolute variance
- Identifying subtotals and grand totals to differentiate calculated fields from raw data
- Exploring dynamic naming and cross-sheet referencing to build comprehensive financial models

Key Findings:
1. Volumes:
   - The company's volumes decreased by 6.85%, from 59,837,639.77 in 2015 to 55,736,290.04 in 2016.

2. Gross Sales Discount and Discounts:
   - Gross sales discount decreased by 5.31%, from $55,548,780.88 in 2015 to $52,597,449.56 in 2016.
   - Discounts decreased by 8.65%, from $3,599,672.36 in 2015 to $3,288,395.59 in 2016.

3. Net Sales:
   - Net sales decreased by 5.08%, from $51,949,108.51 in 2015 to $49,309,053.96 in 2016.

4. Cost of Goods Sold and Gross Profit:
   - Cost of goods sold decreased by 1.35%, from $27,711,508.12 in 2015 to $27,336,503.59 in 2016.
   - Gross profit decreased by 9.35%, from $24,237,600.39 in 2015 to $21,972,550.37 in 2016.

5. KPIs:
   - Gross profit percentage decreased from 46.66% in 2015 to 44.56% in 2016.
   - FDM percentage decreased from 42.92% in 2015 to 40.68% in 2016.

Conclusion and Recommendations:
The analysis indicates that the company experienced a significant decline in its overall performance from 2015 to 2016. The decreases in volumes, net sales, gross profit, and key profitability metrics suggest that the company may have faced increased competition or pricing pressure, leading to lower sales and margins.

To address this decline and improve the company's financial and sales performance, the following recommendations are proposed:

1. Explore strategies to increase sales and optimize costs:
   - Identify and implement initiatives to drive revenue growth, such as expanding into new markets, introducing new products, or enhancing customer engagement.
   - Closely review and optimize the company's cost structure to improve overall profitability.

2. Enhance operational efficiency and identify areas for process improvements:
   - Analyze the company's operations and identify opportunities to streamline processes, reduce waste, and improve productivity.
   - Implement continuous improvement initiatives to drive operational excellence.

3. Closely monitor and analyze the key performance indicators (KPIs):
   - Regularly review and analyze the company's KPIs, such as gross profit percentage and FDM percentage, to identify trends and inform decision-making.
   - Use advanced analytics and data visualization techniques to gain deeper insights into the company's performance.

4. Investigate the root causes of the declines:
   - Conduct a comprehensive investigation to understand the underlying factors contributing to the decreases in volumes, net sales, and gross profit.
   - Develop targeted action plans to address the identified issues and implement effective solutions.

By implementing these recommendations and leveraging the insights gained from the advanced pivot table analysis, the company can work towards regaining its financial and sales performance, and positioning itself for long-term success.





### Analysing and reporting program registraion details 
---
**REPORT FOR PROFESSIONAL COURSE REGISTRATION FOR JULY, 2024.**

**SOURCE OF DATA**


 STUDENTS REGISTRATION DETAILS 

 **WHAT I DID AND RESULT**

1. Removed extra space from the name
=TRIM(D2:D73)

2.Proper sentence case for names
=PROPER(F2:F73)

3. TOTAL NUMBER OF STUDENTS FOR THE SESSION
   
=COUNTA(D2:D72)71

5. PERSONAL REFERRALS 
 COUNT RANGE (TOTAL ROW, RANGE- PERSONAL REFERAL

=COUNTIF(L2:M72,L6)
63
7. SOCIAL MEDIA
=COUNTIF(L2:M72,L68)

PAYMENT SCHEDULE 

6. THREE INSTALLMENTAL PAYMENT
=COUNTIF(J2:J74,J71)
59
6. TWO INSTALLMENTS
=COUNTIF(J2:J73, J10)

PROGRAM REGISTRATION
CIHRM
=COUNTIF(C2:C72,C2), 
26
CICRM 
=COUNTIF(C2:C72,C71)
6

PUTTING DATA INTO TABLE 
select all, INSERT,TABLE

creating  a pivot Table
select all, GO TO INSERT, SELECT PIVOT TABLE


## Steps Performed
1. Data Cleaning  
   - Removed missing Customer IDs  
   - Removed cancelled orders  
   - Created TotalAmount = Quantity * UnitPrice  

2. RFM Calculation  
   - Recency = Days since last purchase  
   - Frequency = Number of transactions  
   - Monetary = Total spending  

3. RFM Segmentation  
   Customers were classified into:  
   - Best Customers  
   - Loyal Customers  
   - Big Spenders  
   - Almost Lost  
   - Lost Customers  
   - Lost Cheap Customers  

4. Final Dataset  
   - RFM metrics were added to customer info  
   - Exported as Customer_Segmentation_Dataset.csv  

5. Dashboard (Power BI)  
   - Donut chart for segmentation distribution  
   - Revenue by segment  
   - Top countries by customer count  
   - Slicer for segment analysis  

## Tools Used
- Python (pandas, matplotlib, seaborn)  
- Jupyter Notebook  
- Power BI  

## Output Files
- Customer_Segmentation_Dataset.csv (final dataset with segments)  
- Customer_Segmentation.pbix (Power BI dashboard)  

# Ecommerce_Order_Delivery_Charges_Verification_Google_sheet
This Google Sheets project tackles an ecommerce challenge, verifying courier charges' accuracy for an Indian company (X). Using internal order data and courier invoices, this solution calculates weights, zones, and charges. The resulting sheet highlights discrepancies, aiding cost validation for X.
Business Scenario
X, a leading ecommerce platform in India, collaborates with multiple courier companies for timely order deliveries. The charges imposed by courier firms are determined by the weight of products and the distance between the warehouse and the customer's delivery address. The company aims to confirm the correctness of these charges due to their significant financial impact.

Solution Approach
Data Compilation: Gather data from X's internal sources, which includes the website order report, SKU master with product weights, and the warehouse-to-delivery-zone mapping. Also, gather the courier company's invoice data that includes AWB numbers, order IDs, shipment weights, pin codes, zones, charges, and shipment type.

Using Google Sheets/Excel: Utilize Google Sheets or Excel for data processing, calculations, and comparisons. Set up appropriate formulas, functions, and tables to facilitate the analysis.

Charges Validation: Calculate the total weight and the corresponding weight slab for each order using SKU weights. Apply the appropriate weight slabs according to the courier company's calculations. Determine delivery zones based on the warehouse-to-zone mapping. Apply charges from the courier company's rate card, considering both "forward charges" and "forward and RTO charges" scenarios.

Resultant Sheet/Workbook: Create a new sheet or workbook in Google Sheets/Excel to document the analysis. This will include columns for order IDs, AWB numbers, weight details, delivery zones, expected charges as per X's data, charges billed by the courier company, and the variance between expected and billed charges.

Repository Structure
ecommerce_charges_verification.xlsx: Sample Excel file showcasing how the data could be organized and calculated.

ecommerce_charges_verification_google_sheets.png: A screenshot illustrating how the same analysis could be performed in Google Sheets.

How to Use
Download the ecommerce_charges_verification.xlsx file or replicate the structure in your preferred spreadsheet software.

Input your own data into the relevant columns based on the provided examples.

Use formulas and functions to perform the weight calculations, charges application, and zone mapping.

Compare the expected charges and the billed charges to identify any discrepancies.

Customize the solution to align with your specific data and business needs.

Note
This project provides a conceptual approach to solving the challenge using Google Sheets/Excel. The data and examples are for demonstration purposes only and do not reflect actual business data.

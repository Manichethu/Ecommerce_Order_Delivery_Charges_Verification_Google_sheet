# Overview:
In this project, you are a data analyst working with a large e-commerce company in India (referred to as "X"). X partners with multiple courier companies for order deliveries, and the charges for each delivery depend on the product's weight and the distance between the warehouse and the customer's address. The goal of this project is to verify if the charges levied by the courier companies for each order are correct. This verification is crucial as the charges significantly impact X's expenses.

# Problem Statement:
X has thousands of daily orders, and they spend a substantial amount on courier charges, approximately Rs. 1 crore per month. They need to ensure that the courier companies are billing them accurately for each order. To tackle this challenge, you have access to two sets of data: X's internal data and courier company invoices.

# Dataset Description:
## 1.) Input Data
Left Hand Side (LHS) Data (X's Internal Data):

Website order report with Order IDs and product details.
SKU master with product weights.
Warehouse pincode to All India pincode mapping.
Right Hand Side (RHS) Data (Courier Company Invoices):

Invoice in CSV format containing AWB Number, Order ID, shipment weight, pickup pincode, delivery pincode, delivery zone, charges per shipment, and shipment type. Courier charges rate card specifying rates at weight slab and pincode levels.

## A) Output Data 1:
Create a resultant CSV/Excel file with the following columns:

Order ID
AWB Number
Total weight as per X (KG)
Weight slab as per X (KG)
Total weight as per Courier Company (KG)
Weight slab charged by Courier Company (KG)
Delivery Zone as per X
Delivery Zone charged by Courier Company
Expected Charge as per X (Rs.)
Charges Billed by Courier Company (Rs.)
Difference Between Expected Charges and Billed Charges (Rs.)

## B) Output Data 2:
Create a summary table to consolidate the results.

Steps to Solve the Challenge:

Calculate the total weight of each shipment based on product weights and weight slabs.
Determine the delivery zone for each order using pincode mapping data.
Compare the calculated values (weight, delivery zone) with the values reported in the courier company invoices.
Calculate the expected charges for each order based on the courier charges rate card.
Compare the expected charges with the charges billed by the courier company to identify any discrepancies.
Generate Output Data 1 and a summary table (Output Data 2) to provide a detailed and summarized view of the discrepancies.

# Key Objectives:
Verify the accuracy of courier charges per order.
Identify and report discrepancies between expected and billed charges.
Ensure that X is not overpaying for courier services.
Streamline the billing process with courier companies for cost optimization

![ecommerce courrier data](https://github.com/ManikantaBN/Ecommerce_Order_Delivery_Charges_Verification_Google_sheet/assets/141845485/4fb66af3-3763-4f29-b8b8-5054d9f52bb1)


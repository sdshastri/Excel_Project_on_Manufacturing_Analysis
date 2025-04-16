# Excel_Project_on_Manufacturing_Analysis
This project analyzes ElectroniTech Manufacturing Co.'s operational data to identify trends in customer behavior, employee efficiency, shipment logistics, and financial transactions using Excel.

####  Objective:

The project aims to analyze ElectroniTech Manufacturing Co. 's operational datasets to gain insights into customer behavior, employee efficiency, shipment logistics, and financial transactions. Students are required to perform comprehensive data analysis using Excel to identify trends, inefficiencies, and potential areas for improvement. Key tasks include data cleaning and integration, detailed analysis of customer and employee data, shipment tracking, financial analysis, and the development of a dynamic dashboard to visualize key metrics. This project will aid in streamlining ElectroniTech Manufacturing Co.'s operations, optimizing supply chain management, and enhancing customer relations, ultimately contributing to the company's strategic decision-making and growth.

1. **Customer.csv**: 

[Customer.csv](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/01398e0c-bc89-4047-8784-59b5795f0f4f/Customer.csv)

This dataset contains information about customers. It's useful for understanding customer demographics and their membership status.

- **`C_ID`**: Customer ID
- **`M_ID`**: Membership ID
- **`C_NAME`**: Customer Name
- **`C_EMAIL_ID`**: Customer Email ID
- **`C_TYPE`**: Customer Type
- **`C_ADDR`**: Customer Address
- **`C_CONT_NO`**: Customer Contact Number

- 2. **Employee_Details.csv**:

[Employee_Details.csv](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/da575b7a-c95f-4028-9dd3-33989fb179f9/Employee_Details.csv)

This dataset includes details of employees. It provides insights into the workforce distribution, roles, and contact information.

- **`E_ID`**: Employee ID
- **`E_NAME`**: Employee Name
- **`E_DESIGNATION`**: Employee Designation
- **`E_ADDR`**: Employee Address
- **`E_BRANCH`**: Employee Branch
- **`E_CONT_NO`**: Employee Contact Number

3. **employee_manages_shipment.csv**:

[employee_manages_shipment.csv](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/e96d07f6-bbe5-449b-833e-a320b2b8cd2f/employee_manages_shipment.csv)

This dataset links employees with shipments they manage. It's crucial for analyzing which employees are responsible for managing specific shipments and their statuses.

- **`Employee_E_ID`**: Employee ID
- **`Shipment_Sh_ID`**: Shipment ID
- **`Status_Sh_ID`**: Status ID for the Shipment

  4. **Membership.csv**:

[Membership.csv](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/eae48561-5bac-463a-a31b-ae251fa98ef5/Membership.csv)

This dataset tracks membership details. This data is useful for understanding the duration of customer memberships.

- **`M_ID`**: Membership ID
- **`Start_date`**: Start date of the membership
- **`End_date`**: End date of the membership

  5. **Payment_Details.csv**:

[Payment_Details.csv](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/d3f180e0-fdc7-4c1a-af49-776a6eab4f67/Payment_Details.csv)

This dataset records payment transactions. It is essential for financial analysis, tracking payment statuses and methods.

- **`Payment_ID`**: Unique ID for each payment
- **`C_ID`**: Customer ID
- **`SH_ID`**: Shipment ID
- **`AMOUNT`**: Payment Amount
- **`Payment_Status`**: Status of the Payment (e.g., PAID, NOT PAID)
- **`Payment_Mode`**: Mode of Payment (e.g., CARD PAYMENT, COD)
- **`Payment_Date`**: Date of Payment

- 6. **Shipment_Details.csv**:

[Shipment_Details.csv](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/6c3f65bf-a65f-4c12-8a2c-e71dabc6eb5b/Shipment_Details.csv)

This dataset provides comprehensive information about shipments. It offers insights into the logistics of shipment, including types, weights, charges, and destinations.

- **`SH_ID`**: Shipment ID
- **`C_ID`**: Customer ID
- **`SH_CONTENT`**: Content of the Shipment
- **`SH_DOMAIN`**: Domain of the Shipment (e.g., Domestic, International)
- **`SER_TYPE`**: Service Type (e.g., Regular, Express)
- **`SH_WEIGHT`**: Weight of the Shipment
- **`SH_CHARGES`**: Charges for the Shipment
- **`SR_ADDR`**: Source Address
- **`DS_ADDR`**: Destination Address

  7. **Status.csv**:

[Status.csv](https://prod-files-secure.s3.us-west-2.amazonaws.com/d1e1bc70-9ede-4c69-84fd-42c5605803a0/ac5e3841-c93a-4a9e-8483-bf53bf798042/Status.csv)

This dataset focuses on the status of shipments. It's useful for tracking the progress and delivery status of shipments.

- **`SH_ID`**: Shipment ID
- **`Current_Status`**: Current status of the shipment (e.g., DELIVERED, NOT DELIVERED)
- **`Sent_date`**: Date when the shipment was sent
- **`Delivery_date`**: Date when the shipment was delivered (if applicable)

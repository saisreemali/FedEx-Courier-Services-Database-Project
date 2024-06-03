# FedEx-Courier-Services-Database-Project
"Designed and implemented a SQL database system for FedEx, enhancing operations, tracking, and customer satisfaction. Streamline processes from order to delivery, ensuring accuracy, security, and scalability. Real-time tracking, multiple user support, and administrative functionalities included."

## Abstract
This project focuses on designing and implementing a database system for FedEx, a global courier and logistics company. The database is built using SQL and aims to streamline and enhance FedEx's operations and tracking capabilities. It includes tables for storing customer information, shipment details, and services. SQL queries are developed to facilitate efficient data retrieval, updates, and analysis. Features such as real-time package tracking and delivery information are incorporated. The project also emphasizes data integrity, security, and scalability to handle the large volume of shipments processed by FedEx. Additionally, the database supports administrative tasks such as user management. The project aims to improve FedEx's overall efficiency, customer satisfaction, and decision-making processes through a robust and well-structured SQL database system.

**Key Words**: Database Management Systems (DBMS); FedEx Services; Order and Shipment Details.

## Introduction
In today's world, daily tasks include transporting goods to meet the needs of individuals, industries, enterprises, and worldwide turnover while also providing the best services at reasonable prices. FedEx is a multinational public company in the United States that provides transportation and courier services worldwide. Customer satisfaction is critical in the transportation industry. This is accomplished by maintaining track of shipping details and pickups, tracking the shipment, delivering on time, and dealing with returns. All these stages must be addressed without redundancy. To accomplish this, we employ integrated database systems that aid in the storage of all information. By using an SQL server, you may handle multiple customers at once and keep track of them at a lower cost.

## Objectives
**Customer Satisfaction**: Prioritize customer satisfaction through efficient tracking and service improvements.
**Core Competence**: Establish system strength, differentiating it through effective database performance.
**Realistic Aims**: Ensure database design is clear and understandable to end users.
**Accuracy and Uniqueness**: Maintain precise, consistent, and non-repetitive data.
**Company Deliveries**: Reflect the company's functionalities and services to customers accurately.
**Motivation and Inspiration**: Foster a collaborative environment that motivates employees.

## Scope
**COSMOS**: Use customer operations service master online system to track product movements.
**Super Trackers**: Utilize handheld devices for scanning package progress.
**Customer Satisfaction**: Reduce wait times and improve service efficiency.
**Multi-Customer System**: Allow multiple users to access data simultaneously.
**Customer Feedback**: Use tools to recognize and rectify system drawbacks.
**Comprehensive Database**: Store detailed customer, delivery, tracking, product, and navigation information.

## User Requirements
- Store customer details such as name, address, and contact details.
- Ensure accurate personal information, order details, and shipping fees.
- Provide customers access to track orders.
- Ensure unique reference details such as order ID, shipping ID, receiver ID, and sender ID.

## Project Requirements
**Tool**: SQL for data retrieval, manipulation, and administration.
**OS**: Windows
**Database**: MySQL Server
**Applications**: MS Word, MS PowerPoint, MS Excel.

## Database Tables
- Order_Details Table
- Customer_Details Table
- Package_Details Table
- Receiver_Customer_Details Table
- FedEx_Loc_Details Table
- Return_Package_Details Table
- Shipment_Services Table
- Shipment_Details Table

## Business Rules
- Customer ID must be unique and 7 digits long.
- Customer names must not be null and have a maximum of 40 characters.
- Customer addresses must be recorded with a maximum of 80 characters.
- Postal codes must be 5 digits long.
- A valid email address is required, limited to 40 characters.
- Each sender and receiver can have multiple orders.
- Order IDs can have multiple packages.
- Shipping costs must not be null.
- Package weights must be recorded and not null.
- Shipping dates must follow the format YYYY MM/DD and cannot be null.
- Shipment IDs must be at least 11 characters long.
- Tracking numbers must be at least 12 characters long.
- Pickup and delivery dates must follow the format YYYY MM/DD, with the pickup date not being later than the delivery date.
- Receiver Customer ID must be 12 digits long.
- Service IDs must be at least 10 characters long.
- Package IDs must be 7 characters long and unique.

## Entity-Relationship Diagram (ERD)
![ERD](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/5fe7e275-f2db-4c9c-a459-65a194fbf5c7)

## Data Dictionary
![Data Dictionary](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/c9183e0f-b0cd-40d5-8da6-d24935cea785)
![Data Dictionary](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/1a7d71f7-7a79-44b3-8c49-15bc9781d488)

## Database Creation
Below are the screenshots for creating schema for FedEx database.
![Database Creation](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/e9140ac8-aa85-4748-849e-d087968c2458)
![Database Creation](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/e8afb372-8cfe-4310-9f87-e20c09e689ff)
![Database Creation](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/d8987709-67c3-4928-ab57-b85d64c12cac)

## Entity Generation and Data Entry
**TABLE 1** 
Customer_Details_Table

![1](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/bf9f69cb-b684-437e-95b7-c2640ddd808c)
![2](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/3878fc3e-8bee-45a9-8c35-e239b8702daa)
![3](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/0266f01b-821b-4985-ad63-f0fbaebe08e7)
![4](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/118ecd3e-25b3-4a58-8f7d-df85fedea755)

**TABLE 2**
FedEX_Loc_Details_Table

![1](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/f9527329-42a2-444e-b25b-84bee3e1195c)
![2](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/63590f3d-2397-4b2a-a844-1dca12d1dcb6)
![3](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/6bf7a3db-5cd7-4a08-aa00-10850a5027be)
![4](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/0a7c2f52-99c3-4c54-b1a2-261971ddcef3)

**TABLE 3**
Order_Details_Table

![1](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/f0891897-bc40-4a0e-b43a-327e124824f8)
![2](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/d1c9f334-f842-4fd0-869b-e5fd4d54a9c1)
![3](https://github.com/saisreemali/FedEx-Courier-Services-Database-Project/assets/170825386/efb11648-cf4d-4dbc-acfb-58966e28a5ff)



## Data Retrieval Using Join Queries
**Question 1** 
List all the orders of receiver corresponding to the state ‘Texas’.
- Query:
Select odr.Order_ID,re.cus_state 
from order_details_table as odr
join receiver_customer_details as re 
on odr.Receiver_ID=re.receiver_id
where re.cus_state='Texas'
- Explanation: The above three order Id’s has receiver customer ID residing in the state ‘Texas’.
  
**Question 2**
List the order ID and date along with the type of package and weight, where its weight is greater is than 30.
- Query:
Select odr.Order_ID,odr.Order_Date,pak.package_Type,pak.weight  
from order_details_table as odr join package_details_table as pak on odr.Order_ID=pak.Order_Number 
where pak.weight>30;
- Explanation: Above results shows the orders details and type of package having weight greater than 30.
  
**Question 3**  
List order ID, order date, receiver customer first name, last name and the state starting with the letter ‘M’.
- Query:
Select odr.Order_ID,odr.order_date,re.cus_first_name,re.cus_last_name,re.cus_state  
from order_details_table as odr join receiver_customer_details re on odr.receiver_id=re.receiver_id 
where re.cus_state like 'M%';
- Explanation: Above are the order and receiver customer detail for the receiver’s state starting with letter ‘M’.
  
**Question 4**
Display order Id and shipping date where shipping date is between 1st Nov 2022 and 31st Dec 2022.
- Query:
Select odr.order_id,pak.ship_date 
from order_details_table as odr join package_details_table pak on odr.Order_ID=pak.Order_Number
where ship_date between '2022-11-01' and '2022-12-31';
- Explanation: Above resultant table displays order ID with shipping date in between the days mentioned in the question.
  
**Question 5**
Display order ID and date which corresponds to the package type ‘FedEx Box Small’ with number of packages greater than 2.

- Query:
SELECT odr.Order_Date ,odr.Order_ID 
from order_details_table as odr join package_details_table as pak on odr.Order_ID=pak.Order_Number 
where pak.Package_Type='FedEx Box Small' AND pak.No_Of_Packages>2;
- Explanation: The result shows the order details whose package type FedEx Small Box with the count of packages is greater than 2.




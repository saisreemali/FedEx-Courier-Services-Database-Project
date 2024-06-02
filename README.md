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
Include the ERD representing the database schema.

## Data Dictionary
Provide a data dictionary explaining the attributes and entities in the database.

## Database Creation
Include screenshots or code snippets showcasing the creation of the database schema.

## Entity Generation and Data Entry
Present tables for customer details, FedEx location details, order details, package details, receiver customer details, return package details, shipment details, and shipment services.

## Data Retrieval Using Join Queries
Provide SQL queries along with explanations for various data retrieval scenarios.

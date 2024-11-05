## Fawry-System API
The Fawry-System API is a comprehensive Spring Boot-based API designed to manage a variety of payment services including mobile recharge, internet payments, and donations. It offers a robust set of features for user and transaction management, wallet handling, and administrative control, all built with SOLID principles and popular design patterns for maintainability and scalability.

# Features
- User Registration: Allows users to register, log in.
- Payment Processing: Supports mobile recharges, internet bill payments, and donations.
- Refunds: Provides users with the ability to request and process refunds.
- Wallet Management: Users can manage their wallet balance, add funds, and make payments.
- Admin Transaction Management: Administrators have control over user transactions, enabling efficient monitoring and handling of payment and refund processes.

# Technologies Used
- Spring Boot: Backend framework for building REST APIs.
- SOLID Principles: Ensures maintainability and scalability.
- Design Patterns: Common patterns like Singleton, Factory, and Strategy, Decorator are applied where suitable.


# Notes import as maven project --- java 11
- right click on src run as java project 
- in postman sign up and log in first before any operation
- for any class, creator enter the attributes in URL like the names in this class 
- for payment we make an alist index 0 is the payment name and other indices is the form info for the payment method so enter values with the same order in the list 
- for providers, we make an alist index 0 is the provider name and other indices is the form input for the provider so enter values with the same order in the list// we make it to avoid concrete classes
- postman collection link --- https://lunar-robot-659340.postman.co/workspace/Team-Workspace~612766d5-421b-415b-8cab-546f8fa818be/collection/24966417-598f7124-a3ad-4217-ac86-7193c007de8c?ctx=documentation

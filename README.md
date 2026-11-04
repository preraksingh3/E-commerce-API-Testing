# E-commerce API Testing Project



## Project Overview

This project focuses on testing E-commerce REST APIs using Postman. It covers positive and negative API scenarios, response validation, status-code verification, and automated test assertions using JavaScript.



##### Project Details

\- Project Name: E-commerce API Testing

\- Tool: Postman

\- API Platform: DummyJSON

\- Testing Type: API Testing

\- Testing Approach: Positive and Negative Testing

\- Total API Requests: 13



##### &#x20;Testing Scope



The project covers the following modules:



1\. Authentication Testing

&#x20;  - Valid login

&#x20;  - Invalid login

&#x20;  - Accessing a protected resource with an invalid token



2\. Product Testing

&#x20;  - Retrieve all products

&#x20;  - Retrieve a product using an invalid ID



3\. Cart Testing

&#x20;  - Add a product with different quantities

&#x20;  - Validate invalid cart data

&#x20;  - Retrieve cart details

&#x20;  - Validate invalid product IDs



4\. Order-related Scenarios

&#x20;  - Validate missing user ID

&#x20;  - Validate invalid product scenarios while creating a cart



5\. Payment Simulation

&#x20;  - Successful payment response

&#x20;  - Failed payment response



&#x20;  Tools and Technologies

&#x20;  - Postman

&#x20;  - DummyJSON REST API

&#x20;  - JavaScript (Postman test scripts)

&#x20;  - Git and GitHub



##### &#x20; Test Execution Summary



|          Metric       | Result |



| Total Test Assertions |   49   |

| Passed                |   49   |

| Failed                |    0   |

| Errors                |    0   |

| Skipped               |    0   |

| Pass Rate             |  100%  |



##### &#x20;Project Deliverables

\- Postman collection JSON export

\- API test scripts

\- Collection Runner execution screenshots

\- Test execution report



##### Important Notes and Limitations

\- DummyJSON is used as a sample API platform. Some operations simulate data changes rather than permanently updating a real database.

\- Payment scenarios use custom mock responses. No real payment transaction is processed.

\- The payment response's HTTP 200 status indicates that the mock endpoint returned a response successfully. The `paymentStatus` field indicates the simulated payment outcome.

\- This project is intended for learning and demonstrating API testing skills.



##### Author

Prerak Singh


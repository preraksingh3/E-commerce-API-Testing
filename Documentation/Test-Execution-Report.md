# Test Execution Report – E-commerce API Testing



### &#x20;1. Project Information



|    Field           |          Details          |

|  Project Name      |    E-commerce API Testing |

|  Testing Tool      |          Postman          |

|  API Platform      |         DummyJSON         |

|  Testing Type      |        API Testing        |

| Execution Method   | Postman Collection Runner |

| Total API Requests |           13              |



#### &#x20;2. Test Execution Summary



|    Metric             | Result |



| Total Test Assertions |   49   |

|    Passed             |   49   |

|    Failed             |    0   |

|    Errors             |    0   |

|    Skipped            |    0   |

|  Pass Percentage      |  100%  |



#### &#x20;3. Test Scenarios Covered



&#x20;Authentication

\- Verify successful login with valid credentials.

\- Verify login failure with invalid credentials.

\- Verify unauthorized access using an invalid token.



&#x20;Product

\- Verify retrieval of all products.

\- Verify response for an invalid product ID.



&#x20;Cart

\- Verify adding a product with quantity 1.

\- Verify adding a product with quantity 2.

\- Verify retrieval of cart details.

\- Verify handling of invalid cart data.



&#x20;Order-related Scenarios

\- Verify handling of an invalid product ID.

\- Verify validation when the user ID is missing.



&#x20;Payment Simulation

\- Verify successful payment simulation.

\- Verify failed payment simulation.



##### &#x20;4. Validation Performed



The following validations were performed using Postman JavaScript test scripts:



\- HTTP status code validation.

\- Response body validation.

\- JSON property validation.

\- Data type and value validation.

\- Array length validation.

\- Error message validation.

\- Authentication token validation.

\- Payment status validation.



##### &#x20;5. Execution Result



All 49 test assertions passed successfully during the latest Collection Runner execution.



No failed tests or execution errors were reported.



##### &#x20;6. Evidence



Six screenshots of the Postman Collection Runner execution results are available in the project's `Screenshots` folder.



##### &#x20;7. Limitations



\- DummyJSON provides simulated API operations; data changes


Introduction

Welcome to the Postman Basics repository! In this repository, you will find a collection of API tests performed during the IT Bootcamp. These tests demonstrate fundamental concepts of API testing using Postman, including GET, POST, PUT, and DELETE operations. The tests were conducted on the Pet Store API, providing a hands-on experience with different HTTP methods and data manipulation techniques.

Prerequisites
Before you begin, make sure you have the following installed:
Postman: If you haven't installed Postman yet, download and install it

API Documentation
The API used for testing is the Pet Store API. You can find the API documentation here. https://petstore.swagger.io/
This documentation provides details about the available endpoints and their functionalities.

Running the Tests
To run the tests, follow these steps:

1.Clone the Repository: Clone this repository to your local machine using the following command:

git clone https://github.com/your-username/postman-basics-petstore.git

2.Import the Collection: Open Postman and import the PetStore.postman_collection.json file located in the cloned repository. This file contains all the requests used for testing.

3.Run the Requests: Once imported, you can run individual requests or the entire collection. Make sure to check the request bodies and parameters to understand how different API operations are performed.

Test Cases
1. GET Request: Get Pet by ID
Endpoint: /pet/{petId}

This test case demonstrates how to retrieve information about a specific pet by its ID.

2. POST Request: Add a New Pet
Endpoint: /pet

This test case shows how to add a new pet to the store by sending a POST request with the pet's details.

3. PUT Request: Update Pet Information
Endpoint: /pet

This test case demonstrates updating an existing pet's information using a PUT request.

4. DELETE Request: Delete a Pet
Endpoint: /pet/{petId}

This test case illustrates deleting a pet from the store using a DELETE request.

Conclusion
These test cases provide a foundation for understanding basic API testing concepts using Postman. Feel free to explore and modify the requests to deepen your understanding of API testing techniques.

Happy testing! If you have any questions or issues, please don't hesitate to reach out.

API Testing – JSONPlaceholder Project
This project demonstrates API testing using Postman with a public mock API.

Objective
To practice API testing by sending requests, validating responses, and verifying system behavior.

Base URL
https://jsonplaceholder.typicode.com

APIs Tested

1. GET Users
	•	Endpoint: /users
	•	Method: GET
	•	Expected: Status code 200 and return user list

2. GET User by ID
	•	Endpoint: /users/1
	•	Method: GET
	•	Expected: Status code 200 and correct user data

3. POST Create User
	•	Endpoint: /users
	•	Method: POST
	•	Expected: Status code 201 and user created

4. PUT Update User
	•	Endpoint: /users/1
	•	Method: PUT
	•	Expected: Status code 200 and data updated

5. DELETE User
	•	Endpoint: /users/1
	•	Method: DELETE
	•	Expected: Status code 200 and user deleted

Test Case Coverage
	•	Positive cases (valid request)
	•	Negative cases (invalid email, user not found)
	•	CRUD operations (GET, POST, PUT, DELETE)
  
Files Included
	•	Postman Collection (.json)
	•	API Test Case (.xlsx)
	•	API Screenshots (.png)

Tools Used
	•	Postman
	•	Excel / Google Sheets

Note
This project uses a public mock API for learning purposes.

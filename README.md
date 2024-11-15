# Testing the Inventory of Devices Web API

## Objective
- Familiarize yourself with a Flask-based web API project.
- Understand the Docker and Docker Compose configuration used in the project.
- Interact with the Inventory of Devices API to understand its functionality.
- Develop test cases for this API (manual testing, no automation required yet).

## Tasks
1. Clone the project repository
	- URL: https://github.com/waad19/mock-api-server

2. Understand Docker and Docker Compose configuration
	- Understand the services defined in docker-compose.yml.</br>
The docker-compose file defines two services: tests and api-mock.
```build: .```
	- Note how the web server is containerized and how it interacts with other services. 
	- Identify the exposed ports and environment variables.

3. Set up and run the application
	- Install Docker and Docker Compose if not already installed.
	- Verify the application is running: Use a tool like curl or Postman.

4. Interact with the Inventory of Devices API
	- Identify the available API endpoints related to the inventory of devices.
	- Analyze the request and response formats.

5. Develop test cases for the Inventory of Devices API
	- Write at least 5 test cases.
	- Focus on both positive and negative scenarios. 
	- Consider edge cases and input validation, if applicable.
	- Test case format.

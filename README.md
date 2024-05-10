
# Postman BookAPI Testing

This project utilizes Postman to interact with the Book API available at (https://simple-books-api.glitch.me). This API allows you to reserve a book. Globals has been configured to facilitate the execution of collections, including variables such as baseURL for storing the common part of the URL, orderId for capturing generated IDs and bookId for capture bookId.

## Project Overview

The aim of this project is to demonstrate the use of Postman for API testing and interaction with the Book API. It includes various API requests such as GET, POST, PUT, PATCH, and DELETE.




## Features

- **Pre-configured Requests:** All requests needed to interact with the BookAPI are pre-configured, including GET, POST, PUT, DELETE, and PATCH methods.
- **URL Variable:** Utilizes the url variable to store the common part of the API URL.
- **ID Tracking:** Uses the orderId and bookId variable to capture generated IDs from API responses
- **Automated Tests:** Each request comes with embedded tests for status codes, response times, and response body content to ensure the API behaves as expected.
- **Authentication:** POST request for API Authentication.




## Requirements

Before you can use this repository effectively, you should have the following installed:

- **Postman:** Ensure you have Postman installed on your system.
- **Newman:** For generating reports through the command line.
## Usage

- Import the provided Postman collection and globals into your Postman application.
- Configure any additional settings or parameters required for the requests.
- Execute the collection to perform the desired API operations.


## Collection Endpoints


- GET Data: Retrieves data from the API.
- POST CustomerInfo: Creates new customer information.
- POST Authentication: Handles user authentication.
- PUT UpdateInfo: Updates existing information.
- PATCH PartialUpdate: Partially updates existing data.
- DELETE DeleteInfo: Deletes specific information.

## Report Generation with Newman

- Newman Tool: Use Newman for command-line execution of collections and report generation.

- Command: Example command to run the collection and generate a report:

```
newman run collection.json --reporters cli,htmlextra

```
## Notes

Use the provided credentials for authentication in API requests.
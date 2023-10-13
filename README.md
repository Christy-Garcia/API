# My API 

# API Name
MyNameAPI
MyNameAPI is a simple API for managing and retrieving personal names. It provides endpoints for adding, updating, retrieving, and deleting names in a database. This API is designed to demonstrate the basic functionality of a RESTful API.

## API
This API allows users to perform basic CRUD (Create, Read, Update, Delete) operations on a database table named names. It includes endpoints for inserting, extracting, updating, and deleting records.

## API
Endpoints
API has several endpoints for different operations:
POST /postName: This endpoint is for inserting data (first name and last name) into the database.
GET /getName: This endpoint is for extracting data (names) from the database.
POST /updateName: This endpoint is for updating data (first name and last name) in the database.
POST /deleteName: This endpoint is for deleting data (names) from the database.

## Request
Payload
{
	“lname”: “hortizuela”,
	“fname”:”manny”
}

 
## Response

{“status”:”success”,”data”:{{“lname”; “hortizuela”, “fname”:”manny”}}}
 
## Usage
You can use this API to interact with a database for basic CRUD operations. You'd send HTTP requests (POST and GET) to the respective endpoints to create, read, update, or delete names in the database.

## License
NO license

## Contributors
Professor Manny Hortizuela Provided tthe parts odes, Database, API, JSON, etc.

## Contact
Information

Include contact
information for inquiries or support.
For inquiries and support, please contact at christy.garcia@student.dmmmsu.edu

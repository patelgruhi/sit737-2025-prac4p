# sit737-2025-prac4p
Calculator Microservice
A simple Node.js microservice for basic arithmetic operations with logging.

Setup

Install dependencies:
npm install  

Run the service:
node app.js  

API Endpoints
Method	Endpoint	Description
GET	/add?a=X&b=Y	Addition
GET	/subtract?a=X&b=Y	Subtraction
GET	/multiply?a=X&b=Y	Multiplication
GET	/divide?a=X&b=Y	Division (handles division by zero)

Logging
logs/all.log → All requests

logs/errors.log → Errors
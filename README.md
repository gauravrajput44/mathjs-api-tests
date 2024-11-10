# Math.js API Testing Project

This repository contains postman collections for the [Math.js API](https://api.mathjs.org/) GET and POST endpoints. 

## Overview

The project includes:
- Postman Collection
- Test data files
- [High level API checklist](https://github.com/gauravrajput44/mathjs-api-tests/blob/main/api_checklist.md)

## Endpoints Covered
GET and POST for the `http://api.mathjs.org/`

## How to use collection and test data
- For the GET request, import [postman-collections/MathJs GET API Tests With CSV Data.postman_collection.json](https://github.com/gauravrajput44/mathjs-api-tests/blob/main/postman-collections/MathJs%20GET%20API%20Tests%20With%20CSV%20Data.postman_collection.json) in the postman

- Run the collection and use the [test data file](https://github.com/gauravrajput44/mathjs-api-tests/blob/main/test-data/get_api_test_data.csv) as input to run the tests

- For the POST request, import [postman-collections/MathJs POST API Tests.postman_collection.json](https://github.com/gauravrajput44/mathjs-api-tests/blob/main/postman-collections/MathJs%20POST%20API%20Tests.postman_collection.json) in the postman and run the tests

## Test Cases for the GET Endpoint

The GET collection contains test cases for the GET API of the MathsJs service.

The tests are executed using multiple data sets provided in the `get_api_test_data.csv` file. 

### Testing Scenarios

1. **Performance**
   - Ensures that the response time is consistently under 1 second

2. **Data Validation**
   - Verifies that the response status code and data match the expected values defined in `get_api_test_data.csv`

3. **Error Handling**
   - Confirms correct handling of error cases

Each test scenario uses varied inputs from `get_api_test_data.csv` to ensure comprehensive coverage.

## Test Cases for the POST Endpoint

This collection includes test cases for the `POST` API of the MathsJs service.

### Test Scenarios

1. **Complex Mathematical Operations**
   - Validate the response code and structure
   - Ensure the evaluated expression yields the correct value

2. **Variable Assignment and References**
   - Verify that variables are assigned correctly
   - Confirm variables are referenced accurately in expressions

3. **Unit Conversion**
   - Ensure unit conversions are accurately performed

4. **Invalid Expression Handling**
   - Confirm proper handling of invalid expressions
   - Verify appropriate error messages are returned

5. **Precision Testing**
   - Check the accuracy of results with varying precision levels
   - Validate decimal place handling




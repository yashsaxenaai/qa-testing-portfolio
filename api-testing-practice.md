# API Testing Practice

## Objective
To practice basic REST API testing using GET, POST, PUT and DELETE requests.

## API Used
JSONPlaceholder – Public REST API for testing and practice.

## Test Scenarios

| Test Case ID | Method | Test Scenario | Expected Result |
|---|---|---|---|
| API_001 | GET | Get a list of users | Response status should be 200 |
| API_002 | GET | Get user by valid ID | User details should be returned |
| API_003 | GET | Get user with invalid ID | Appropriate response should be returned |
| API_004 | POST | Create a new user | User should be created successfully |
| API_005 | PUT | Update existing user | User details should be updated |
| API_006 | DELETE | Delete an existing user | User should be deleted successfully |

## Validations

- Verify HTTP status code
- Verify response body
- Verify response headers
- Verify JSON response structure
- Verify required fields
- Verify response time

## Tools

- Postman
- REST API
- JSON

## Note

This is a personal API testing practice project created to demonstrate basic API testing concepts.

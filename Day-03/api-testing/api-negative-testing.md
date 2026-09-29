# API Negative Testing

## Objective

I practiced negative testing for APIs by sending invalid or incomplete requests.

## Test Cases

| Test Case | Request                                       | Expected Result                                         |
| --------- | --------------------------------------------- | ------------------------------------------------------- |
| NT-01     | Send request with invalid endpoint            | API should return `404 Not Found`                       |
| NT-02     | Send request with missing required data       | API should return an appropriate validation error       |
| NT-03     | Send request with invalid data format         | API should reject the request with an appropriate error |
| NT-04     | Access a protected API without authentication | API should return `401 Unauthorized`                    |
| NT-05     | Send an invalid request                       | API should return an appropriate `4xx` error            |

## Key Learning

Negative API testing helps verify that the API handles invalid inputs, missing data, and unauthorized requests correctly instead of returning unexpected results.

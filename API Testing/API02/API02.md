API 2: POST To All Products List
Test Case ID: API-002
Test Description: Verify the response when sending a POST request to /api/productsList.
Test Steps:
Send a POST request to /api/productsList.
Observe the response code.
Verify that the request is rejected with a 405 Method Not Allowed status.
Expected Result:
Response code should be 405 Method Not Allowed.
Actual Result:
{"responseCode": 405, "message": "This request method is not supported."
Test Status: Pass
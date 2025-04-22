API 4: PUT To All Brands List
Test Case ID: API-004
Test Description: Verify the response when sending a PUT request to /api/brandsList.
Test Steps:
Send a PUT request to /api/brandsList.
Observe the response code.
Verify that the request is rejected with a 405 Method Not Allowed status.
Expected Result:
Response code should be 405 Method Not Allowed.
Actual Result:
{"responseCode": 405, "message": "This request method is not supported."}
Test Status: Pass
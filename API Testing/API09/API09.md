API 9: DELETE To Verify Login
Test Case ID: API-009
Test Description: Verify the response when trying to DELETE using the /verifyLogin endpoint.
Test Steps:
Send a DELETE request to /api/verifyLogin.
Observe the response code.
Verify that the request is rejected with a 405 Method Not Allowed status.
Expected Result:
Response code should be 405 Method Not Allowed.
Actual Result:
{"responseCode": 405, "message": "This request method is not supported."}
Test Status: Pass
API 8: POST To Verify Login without email parameter
Test Case ID: API-008
Test Description: Verify the response when the email parameter is missing from the login request.
Test Steps:
Send a POST request to /api/verifyLogin with the payload:
{
"password": "password123"
}
Observe the response code.
Verify that the response indicates a missing email parameter.
Expected Result:
Response code should be 400 Bad Request.
The response body should mention that the email parameter is required.
Actual Result:
{"responseCode": 400, "message": "Bad request, email or password parameter is missing in POST request."}
Test Status: Pass
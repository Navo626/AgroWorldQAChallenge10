API 7: POST To Verify Login with valid details
Test Case ID: API-007
Test Description: Verify the response when posting valid login credentials.
Test Steps:
Send a POST request to /api/verifyLogin with the payload:
{
"email": "valid@example.com",
"password": "correctpassword"
}
Observe the response code.
Verify that the response contains a message confirming the user exists.
Expected Result:
Response code should be 200 OK.
The response body should confirm that the user exists.
Actual Result:
{"responseCode": 200, "message": "User exists!"}
Test Status: Pass
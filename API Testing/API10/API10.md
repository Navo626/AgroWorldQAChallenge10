API 10: POST To Verify Login with invalid details
Test Case ID: API-010
Test Description: Verify the response when posting invalid login credentials.
Test Steps:
Send a POST request to /api/verifyLogin with the payload:
{
"email": "navo1.jayakodi@gmail.com",
"password": "112"
}
Observe the response code.
Verify that the response indicates the user is not found or invalid credentials.
Expected Result:
Response code should be 404 Not Found or similar.
The response body should indicate "User not found."
Actual Result:
{"responseCode": 404, "message": "User not found!"}
Test Status: Pass
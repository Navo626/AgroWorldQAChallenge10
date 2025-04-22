API 6: POST To Search Product without search_product parameter
Test Case ID: API-006
Test Description: Verify the response when sending a POST request to search for a product without providing the search_product parameter.
Test Steps:
Send a POST request to /api/searchProduct with the empty payload:
Observe the response code.
Verify that the response indicates a bad request (400).
Expected Result:
Response code should be 400 Bad Request.
The response body should indicate that the search_product parameter is required.
Actual Result:
{"responseCode": 400, "message": "Bad request, search_product parameter is missing in POST request."}
Test Status:  Pass
API 3: Get All Brands List
Test Case ID: API-003
Test Description: Verify the response of the GET method for retrieving all brands.
Test Steps:
Send a GET request to /api/brandsList.
Verify that the response status code is 200.
Verify the structure of the response to include all brand names.
Expected Result:
Response code should be 200 OK.
The response body should contain a list of brands like Polo, H&M, etc.
Actual Result:
{"responseCode": 200, "brands": [{"id": 1, "brand": "Polo"}, {"id": 2, "brand": "H&M"}, {"id": 3, "brand": "Madame"},
Test Status: Pass
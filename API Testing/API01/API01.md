API 1: Get All Products List
Test Case ID: API-001
Test Description: Verify the response of the GET method for retrieving all products.
Test Steps:
Send a GET request to /api/productsList.
Verify that the response status code is 200.
Verify the structure of the response to include product details such as id, name, price, etc.
Expected Result:
Response code should be 200 OK.
The response body should contain a list of products with correct fields like id, name, price, brand, and category.
Actual Result:
{"responseCode": 200, "products": [{"id": 1, "name": "Blue Top", "price": "Rs. 500", "brand": "Polo", "category": {"usertype": {"usertype": "Women"}, "category": "Tops"}}, {"id": 2, "name": "Men Tshirt", "price": "Rs. 400", "brand": "H&M", "category": {"usertype": {"usertype": "Men"}, " ……………..etc.
Test Status: Pass
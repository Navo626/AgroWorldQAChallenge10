API 5: POST To Search Product
Test Case ID: API-005
Test Description: Verify the response when sending a POST request to search for a product.
Test Steps:
Send a POST request to /api/searchProduct with the payload:
{
"search_product": "dress"
}
Observe the response code.
Verify that the response contains a list of products matching the search term "dress".
Expected Result:
Response code should be 200 OK.
The response body should contain a list of products related to "dress".
Actual Result:
{"responseCode": 200, "products": [{"id": 3, "name": "Sleeveless Dress", "price": "Rs. 1000", "brand": "Madame",
"category": {"usertype": {"usertype": "Women"}, "category": "Dress"}}, {"id": 4, "name": "Stylish Dress", "price": "Rs.
1500", "brand": "Madame", "category": {"usertype": {"usertype": "Women"}, "category": "Dress"}}, {"id": 16, "name":
"Sleeves Top and Short - Blue & Pink", "price": "Rs. 478", "brand": "Babyhug", "category": {"usertype": {"usertype":
"Kids"}, "category": "Dress"}}, {"id": 19, "name": "Sleeveless Unicorn Patch Gown - Pink", "price": "Rs. 1050", "brand":
"Allen Solly Junior", "category": {"usertype": {"usertype": "Kids"}, "category": "Dress"}}, {"id": 20, "name": "Cotton
Test Status : Pass
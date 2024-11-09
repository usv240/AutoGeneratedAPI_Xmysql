1. Title: Get All Products
    Description: This GET request retrieves all products from the database, displaying a list with details like product_id, name, description, price, and stock.
    URL: http://localhost:3000/api/products
    Screenshot File: https://drive.google.com/file/d/1liLu-XlTwWX170KqhGu1FFTLm-hQdMUX/view?usp=sharing

2. Title: Get Product by ID
    Description: This GET request retrieves a specific product by its product_id. In this example, the product with product_id = 1 is fetched.
    URL: http://localhost:3000/api/products/1
    Screenshot File: https://drive.google.com/file/d/1Cozbqaf3d6UGH1b-JrdVex_SEDFyMtPY/view?usp=sharing

3. Title: Create New Product
    Description: This POST request adds a new product to the database. The request includes name, description, price, and stock in the JSON body, creating a new entry in the products table.
    URL: http://localhost:3000/api/products
    Screenshot File: https://drive.google.com/file/d/1xLZh-fc-ZHliI3w2gFfKXZ37i6C0VJmA/view?usp=sharing

4. Title: Update Product by ID (PUT)
    Description: This PUT request updates the entire product data for a specified product_id. In this example, product_id = 5 is updated with new values for name, description, price, and stock.
    URL: http://localhost:3000/api/products/5
    Screenshot File: https://drive.google.com/file/d/1Fkmjm5mgg4k6opbUgOILr3k4c4zY66Xm/view?usp=sharing

5. Title: Modify Product Stock (PATCH)
    Description: This PATCH request modifies the stock attribute of a specific product. Only the stock field is updated for the product with product_id = 1.
    URL: http://localhost:3000/api/products/1
    Screenshot File: https://drive.google.com/file/d/12gCw5qZdYn2HxTa7yJKFzDCnbyfx6Ssw/view?usp=sharing

6. Title: Delete Product by ID
    Description: This DELETE request removes a product from the database using its product_id. Here, the product with product_id = 1 is deleted.
    URL: http://localhost:3000/api/products/1
    Screenshot File: https://drive.google.com/file/d/1CS8G0hUWoFDPvKrdxvdqkPgBRjPS8nbM/view?usp=sharing

7. Title: Count Total Products
    Description: This GET request returns the total count of products in the database. The response shows the number of rows in the products table.
    URL: http://localhost:3000/api/products/count
    Screenshot File: https://drive.google.com/file/d/1wxGz_ottunQI7U4jqaH8gd4ZZ2w1tc2O/view?usp=sharing

8. Title: Setup Database API Connection in DreamFactory
    Description: This screenshot shows the configuration settings for creating a database API connection in DreamFactory. It includes details like Connection String, Host, Database, and credentials.
    URL: No specific URL, configuration setup.
    Screenshot File: https://drive.google.com/file/d/1klv0_DdAm8P0coPGuNQM8-hGc3hvQ6kt/view?usp=sharing

9. Title: Xmysql CLI Setup and Initialization
    Description: This command line screenshot shows the Xmysql setup process, including altering the MySQL authentication method and generating REST APIs for the database at localhost:3000.
    URL: Command Line Setup
    Screenshot File: https://drive.google.com/file/d/1Sjb6eQY5XsInHJxCSGnxpYMZgycvJMt1/view?usp=sharing

10. Title: Retrieve All Products After Setup
    Description: This GET request demonstrates retrieving all products from the products table after successful setup and API generation.
    URL: http://localhost:3000/api/products
    Screenshot File: https://drive.google.com/file/d/1x7LD4Nx8r-8-zf1w8mqlGuWErRMucD54/view?usp=sharing


11. Title: Add Multiple Products (Bulk Insert)
    Description: This POST request adds multiple products to the database in one go. The request body includes an array of product objects with fields like name, description, price, and stock.
    URL: http://localhost:3000/api/products/bulk
    Screenshot File: https://drive.google.com/file/d/1yJlaauhBAroYRNaODFzN8mRmJaDpgBrO/view?usp=sharing

12. Title: Delete Multiple Products by IDs (Bulk Delete)
    Description: This DELETE request removes multiple products from the database based on their IDs. Here, products with IDs 1, 2, and 3 are deleted in a single request.
    URL: http://localhost:3000/api/products/bulk?_ids=1,2,3
    Screenshot File: https://drive.google.com/file/d/1qzbn6yW2-t2bvTQZOFPwiyEERBhNcyWQ/view?usp=sharing

13. Title: Aggregate Price Data
    Description: This GET request performs an aggregate function on the price field in the products table, calculating metrics like minimum, maximum, average, sum, and standard deviation of product prices.
    URL: http://localhost:3000/api/products/aggregate?_fields=price
    Screenshot File: https://drive.google.com/file/d/1qnWgwXN2i2gwuwG1RzRAX0D6sevZMaOY/view?usp=sharing


14. Title: Group Products by Price
    Description: This GET request groups products by their price. It shows the count of products for each unique price in the products table.
    URL: http://localhost:3000/api/products/groupby?_fields=price
    Screenshot File: https://drive.google.com/file/d/19QgYvig3pPwdjZ3gszQSYrStaiBQKQxX/view?usp=sharing


15. Title: Price Distribution Chart
    Description: This GET request creates a chart distribution of product prices. It groups prices within specified ranges to visualize the distribution across different price segments.
    URL: http://localhost:3000/api/products/chart?_fields=price&min=0&max=100&step=10
    Screenshot File: https://drive.google.com/file/d/1zQty3u1nMSUvsyH-LElj5GcitrIPHYN0/view?usp=sharing


16. Title: Describe Products Table Schema
    Description: This GET request retrieves the schema details of the products table, showing each column’s properties such as field name, data type, nullability, and key status.
    URL: http://localhost:3000/api/products/describe
    Screenshot File: https://drive.google.com/file/d/1eEQ2gMQJbgVkxpHZrh-eQ9oVQkLb2tSj/view?usp=sharing
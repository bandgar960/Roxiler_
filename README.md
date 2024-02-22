Backend Task Data Source THIRD PARTY API URL : https://s3.amazonaws.com/roxiler.com/product_transaction.json REQUEST METHOD : GET RESPONSE FORMAT : JSON GET Create API to initialize the database. fetch the JSON from the third party API and initialize the database with seed data. You are free to define your own efficient table / collection structure Instruction All the APIs below should take month ( expected value is any month between January to December) as an input and should be matched against the field dateOfSale regardless of the year. GET Create an API to list the all transactions

API should support search and pagination on product transactions
Based on the value of search parameters, it should match search text on product title/description/price and based on matching result it should return the product transactions
If search parameter is empty then based on applied pagination it should return all the records of that page number
Default pagination values will be like page = 1, per page = 10
GET Create an API for statistics



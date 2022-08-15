Points Calculator based on customer and transaction on localhost port 8091
The rest API to get customer rewards based on customer Id
The package name is structured as com.customer.retail
Exception is ResponseEntity thrown if customer does not exists.
H2 in-memory database to store the information.
Install H2 db locally and run it . change the db settings in application.properties file.
Do run the scrip.sql on H2 in memory DB to prepare the test data.
postman link : http://localhost:8091/customer/reward/10022 
ı added H2 folders for creating table and records.
hithup link :https://github.com/yasinagan/reailAward.git
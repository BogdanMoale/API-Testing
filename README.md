# API-Testing
API Testing in Postman

----------------

**Description:** 
Get all articles about Oneplus 7t smartphone from a specific date until the present day , sorted by recent first.

**Steps to Reproduce:**
1. Go to https://newsapi.org/v2/everything?q=Oneplus7t&from=2023-06-31&sortBy=publishedAt&apiKey=b7f1eb4fa60842f5ae8e579f27e829a5 in Postman
2. Send the endpoint with GET request

**Expected result:**
User should be able to get all articles about Oneplus 7t from the date 2023-06-31 forward, sorted by the recent articles first

**Query Params:** <br />
* q: Oneplus7t  <br />
* from: 2023-06-31  <br />
* sortBy: publishedAt  <br />
* apiKey: b7f1eb4fa60842f5ae8e579f27e829a5  <br />

----------------

**Description:** 
Get all articles mentioning JavaScript from a start date to an end date, sorted by popular publishers first.

**Steps to Reproduce:**
1. Go to https://newsapi.org/v2/everything?q=JavaScript&from=2023-07-30&to=2023-07-30&sortBy=popularity&apiKey=b7f1eb4fa60842f5ae8e579f27e829a5 in Postman
2. Send the endpoint with GET request

**Expected result:**
User should be able to get all articles mentioning JavaScript from selected start date to selected end date

**Query Params:**<br />
* q: JavaScript  <br />
* from: 2023-07-30  <br />
* to: 2023-07-30  <br />
* sortBy: popularity  <br />
* apiKey: b7f1eb4fa60842f5ae8e579f27e829a5  <br />


----------------

**Description:** 
Top business headlines in the Romania right now.

**Steps to Reproduce:**
1. Go to https://newsapi.org/v2/top-headlines?country=ro&category=business&apiKey=b7f1eb4fa60842f5ae8e579f27e829a5 in Postman
2. Send the endpoint with GET request

**Expected result:**
User should be able to get all articles mentioning Top business headlines in the Romania in the pressent day

**Query Params:** <br />
* country: ro  <br />
* category: business  <br />
* apiKey: b7f1eb4fa60842f5ae8e579f27e829a5  <br />

----------------
**Description:** 
All articles published by the Wall Street Journal in the last 6 months, sorted by recent first.

**Steps to Reproduce:**
1. Go to https://newsapi.org/v2/everything?domains=wsj.com&apiKey=b7f1eb4fa60842f5ae8e579f27e829a5 in Postman
2. Send the endpoint with GET request

**Expected result:**
User should be able to get all articles published by the Wall Street Journal in the last 6 months

**Query Params:** <br />
* domains: wsj.com  <br />
* apiKey: b7f1eb4fa60842f5ae8e579f27e829a5  <br />

----------------
**Description:** 
Get information about a specific movie: Terminator 3

**Steps to Reproduce:**
1. Go to http://www.omdbapi.com/?apikey=2e9b645e&t=terminator 3&type=movie&y=2003&plot=ful&r=json in Postman
2. Send the endpoint with GET request

**Expected result:**
User should be able to get information about the movie : Terminator 3

**Query Params:** <br />
* apikey: 2e9b645e  <br />
* t: Terminator 3  <br />
* type: movie  <br />
* y: 2003  <br />
* plot: full  <br />
* r: json  <br />

----------------
**Description:** 
Get information about a specific series: The walking dead 

**Steps to Reproduce:**
1. Go to http://www.omdbapi.com/?apikey=2e9b645e&t=The walking dead &type=series in Postman
2. Send the endpoint with GET request

**Expected result:**
User should be able to get information about the tv series : The walking dead
**Query Params:** <br />
* apikey: 2e9b645e  <br />
* t: The walking dead  <br />
* type: series  <br />
----------------

**Description:** 
Get all users from database

**Steps to Reproduce:**
1. Go to https://qachallenge.ro/api/test_api.php?action=fetch_all in Postman
2. Send the endpoint with GET request

**Expected result:**
User should be able to get all the information form database

**Query Params:** <br />
action=fetch_all<br />

----------------
**Description:** 
Get single user from database

**Steps to Reproduce:**
1. Go to http://qachallenge.ro/api/test_api.php?action=fetch_single&id=736 in Postman
2. Send the endpoint with GET request

**Expected result:**
User should be able to get the information about the selected id form database: "first_name":"Bogdan","last_name":"M"

**Query Params:** <br />
action=fetch_single<br />
id=736<br />

----------------
**Description:** 
Insert user in database

**Steps to Reproduce:**
1. Go to http://qachallenge.ro/api/test_api.php?action=insert in Postman
2. Send the endpoint with POST request

**Expected result:**
User should be able to insert in database the provided first_name and last_name

**Query Params:** <br />
action=insert<br />

**Body Params:** <br />
first_name = Test <br />
last_name = T <br />

----------------
**Description:** 
Update user in database

**Steps to Reproduce:**
1. Go to http://qachallenge.ro/api/test_api.php?action=update in Postman
2. Send the endpoint with POST request

**Expected result:**
User should be able to update in database the provided first_name,last_name based on the id

**Query Params:** <br />
action=update<br />


**Body Params:** <br />
id = 737
first_name = Test <br />
last_name = T <br />

----------------
**Description:** 
Delete user in database

**Steps to Reproduce:**
1. Go http://qachallenge.ro/api/test_api.php?action=delete&id=737 in Postman
2. Send the endpoint with POST request

**Expected result:**
User should be able to delete the record from database at the desired id

**Query Params:** <br />
action=delete<br />
id = 737 <br />

   













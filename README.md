# API-Testing
API Testing in Postman

----------------

**Description:** 
Get all articles about Oneplus 7t smartphone from a specific date ubtil the present day , sorted by recent first.

**Steps to Reproduce:**
1. Go to https://newsapi.org/v2/everything?q=Oneplus 7t&from=2023-06-31&sortBy=publishedAt&apiKey=b7f1eb4fa60842f5ae8e579f27e829a5
2. Send the endpoint

**Expected result:**
User should be able to get all articles about Oneplus 7t from the date 2023-06-31 forward, sorted by the recent articles first

**Test Data:**
q: Oneplus 7t
from: 2023-06-31
sortBy: publishedAt
apiKey: b7f1eb4fa60842f5ae8e579f27e829a5

----------------

**Description:** 
Get all articles mentioning JavaScript from a start date to an end date, sorted by popular publishers first.

**Steps to Reproduce:**
1. Go to https://newsapi.org/v2/everything?q=JavaScript&from=2023-07-30&to=2023-07-30&sortBy=popularity&apiKey=b7f1eb4fa60842f5ae8e579f27e829a5
2. Send the endpoint

**Expected result:**
User should be able to get all articles mentioning JavaScript from selected start date to selected end date

**Test Data:**
q: JavaScript
from: 2023-07-30
to: 2023-07-30
sortBy: popularity
apiKey: b7f1eb4fa60842f5ae8e579f27e829a5


----------------

**Description:** 
Top business headlines in the Romania right now.

**Steps to Reproduce:**
1. Go to https://newsapi.org/v2/top-headlines?country=ro&category=business&apiKey=b7f1eb4fa60842f5ae8e579f27e829a5
2. Send the endpoint

**Expected result:**
User should be able to get all articles mentioning Top business headlines in the Romania in the pressent day

**Test Data:**
country: ro
category: business
apiKey: b7f1eb4fa60842f5ae8e579f27e829a5

----------------
**Description:** 
All articles published by the Wall Street Journal in the last 6 months, sorted by recent first.

**Steps to Reproduce:**
1. Go to https://newsapi.org/v2/everything?domains=wsj.com&apiKey=b7f1eb4fa60842f5ae8e579f27e829a5
2. Send the endpoint

**Expected result:**
User should be able to get all articles published by the Wall Street Journal in the last 6 months

**Test Data:**
domains: wsj.com
apiKey: b7f1eb4fa60842f5ae8e579f27e829a5





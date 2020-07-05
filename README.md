# API_Automation
REST API Automation Test Suite by Postman and newman (the cli companion for postman).

# Steps:-
1. Download postman from official site. it is free.
2. Import API_Auomation.postman_dump file into postman. This will import collections as well as environment variables.
3. Run collection in Runner by selecting - 
  a. collection name.
  b. select environment as Test
  c. provide iteration number.
  d. click on run.
  
# Few Details :-
1. Name and Description can be use to define name and details about collections or requests.
2. Authorization at collection level can be used to define authorization for all requests define under the collections.
3. Folders can be created under collections to logically group requests.
4. Pre-request Scripts can be use to write scripts which get executed before request.
5. Tests can be used to write test scripts/assertion which get executed after request.
6. postman supports JavaScripts for scripting and supports "Chai Assertion Library".

# Reference - 
To download postman :-https://www.postman.com/downloads/
To download node :- https://nodejs.org/en/download/
command to install newman package :- npm install -g newman
command to install newman-reporter-html package :- npm install -g newman-reporter-html
command to install newman-reporter-htmlextra package :- npm install -g newman-reporter-htmlextra
command to run newman :- newman run <collectionName.json> -e <Env.json> -d <datafile.json> -r htmlextra

Test request response site :- https://reqres.in/
Chai Assertion Library :- https://www.chaijs.com/
Postman Scripts :- https://learning.postman.com/docs/postman/scripts/postman-sandbox-api-reference/

# Note:- 
html will give simple report whereas, htmlextra will give more advance report.
newman cli can be integrated with Jenkins to auto-run API Integration test suite and publish test report via email.

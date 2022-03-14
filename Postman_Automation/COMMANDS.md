# README #

This README would describe Executing Postman Collection in Command Line.

### Installing & Running Newman ###

* Install node.js
* $ npm install -g newman
* $ newman run Automation_Test.postman_collection.json -e enviroment.json -g global.json

### Report Generation ###

* $ newman run Automation_Test.postman_collection.json -e enviroment.json -g global.json --reporters cli,json --reporter-json-export results/outputfile.json


### Installing & Running HTML Custom Reporters  ###

* $ npm install -g newman-reporter-htmlextra
* $ newman run Trio_QA_Regression.postman_collection.json -e UAT.TRIO.CLOUD.postman_environment.json -r htmlextra
* $ newman run Trio_QA_Regression.postman_collection.json -e UAT.TRIO.CLOUD.postman_environment.json -r htmlextra,cli --reporter-htmlextra-title "Finch QA Regression"




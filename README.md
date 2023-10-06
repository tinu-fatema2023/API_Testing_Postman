# PostmanTool and REST API:
Postman is a comprehensive API testing tool that simplifies creating, testing, and documenting APIs. REST APIs are a very common and important type of API that uses HTTP protocol for data transmission. we can easily implement the REST API approach by using Postman REST Client. It can handle various types of HTTP requests ranging from GET, POST, PUT, PATCH, DELETE converting the API to code for other languages like JavaScript, Python, etc. Here in the picture, I have shown the different methods:

![Screenshot_1](https://github.com/tinu-fatema2023/API_Testing_Postman/assets/143411063/8d4f488f-bd08-4446-bd5f-5acfd1db7a93)
# Adding Environment Variables:
We can use variables in Postman to define and reference values in your collections, environments, requests, and scripts.

![Screenshot 2023-09-26 211910](https://github.com/tinu-fatema2023/API_Testing_Postman/assets/143411063/19450e66-c322-4c1d-9843-c58feee1a689)
# API Response Validations
PM is a postman built in  library which is providing set a number of functions to add validation points and those functions are developed by using JavaScript. In the test tab we can add the validation point/assertion to  
check the validation of status code, cookies, header and different field value of response body.

![Screenshot_3](https://github.com/tinu-fatema2023/API_Testing_Postman/assets/143411063/1bde5188-ec99-4e91-a649-6948591744d7)
# Dynamic Variables in API testing
Here we uses the faker library in psotman to generate sample data, including random names, addresses, email addresses, and much more. To use dynamic variables in pre-request or test scripts, you need to use pm.variables.replaceIn().

![Screenshot_4](https://github.com/tinu-fatema2023/API_Testing_Postman/assets/143411063/1067d24a-db79-4e6e-87df-d3b7c05d0bc2)
# Generating HTML report using Newman:
Newman is a command-line Collection Runner for Postman. It enables to run and test a Postman Collection directly from the command line.Command are given below:
 - newman run 1st_REST_API_Methods.postman_collection.json -e testing_api.postman_environment.json -r cli,html
 - newman run 1st_REST_API_Methods.postman_collection.json -e testing_api.postman_environment.json -r cli,htmlextra
   
![newmanreport](https://github.com/tinu-fatema2023/API_Testing_Postman/assets/143411063/8516762d-ae31-40dc-a284-60189a2f33e0)

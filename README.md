# Day01_Spring
Basic Spring application printing Hello World

SpringApp is a simple Spring Boot application that provides a REST API endpoint to demonstrate the basics of building web applications with Spring Boot. 
The application runs on an embedded server (default port 8080) and exposes a /hello endpoint that accepts an optional query parameter name. By default, visiting http://localhost:8080/hello responds with "Hello World!", but if a name is provided (e.g., http://localhost:8080/hello?name=Alice), it dynamically personalizes the greeting to "Hello Alice!". This lightweight project is ideal for learning Spring Boot’s auto-configuration, REST controller mappings, and running standalone Java applications with minimal setup.

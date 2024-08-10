# LearnSpring
## Description
Repository documenting my learning process with Java Spring
## Build Projects
Projects are all built in a similar fashion. Here is a step-by-step guide:
- Open terminal
- Change directories into selected project directory directory (Ex: /CreateSimpleSpring)
- Run .\mvnw.cmd spring-boot:run on Windows or ./mvnw spring-boot:run on Linux/Mac

## Projects
### RestfulWebService: 
- Test project that builds, compiles, and runs on localhost:8080/greeting endpoint
- Uses RestfulWebService guide from Spring website
- Use atomic counter and a greeting POD object to return a customized JSON response at /greeting endpoint
- To try out this project:
  - Run build commands in Build Projects section
  - Open localhost:8080/greeting?name=YourNameHere in a browser of your choice

### CreateSimpleSpring: 
- Test project that builds, compiles, and runs on localhost:8080/hello endpoint
- Uses quick-start guide from Spring website
- To try out this project:
  - Run build commands in Build Projects section
  - Open localhost:8080/hello?name=YourNameHere in a browser of your choice

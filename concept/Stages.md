# **Stages**

Development is divided into the following stages:

- establish basic concepts and goals of the project
  ***done*** 
- identify technologies and infrastructure to use 
  **done**
- set up development environment
  (git, ticket system, local dev environment)
- implement prototype
  - create database structures
  - business logic on client & server
  - interface which allows room creation, joining, guessing & basic rewards
- word cloud, sophisticated reward system 
  (exponential curve?)
- add WebRTC voice chat implementation



**Optionals:**

- track statistics to empirically establish how hard words are. Then perform binary search to present players with words optimal for their level. 



## Technologies & Infrastructure

- Spring Boot server backend, React for Frontend
  for the time being; Spring Boot's internal webserver, later probably others. 
- PostgreSQL as database
- local dev environment; deploy on AWS EC2 once finished
- WebRTC for voice chat implementation
  look into libraries to specify which ones work best with Spring Boot/the Webserver
  might also use dedicated server with nginx/C++ implementation for performance reasons. 
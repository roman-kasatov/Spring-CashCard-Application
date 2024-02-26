## Complete REST API application for managing virtual cash cards created with Spring Boot.

### Technologies
  + Spring Boot
  + Spring Web
  + Spring Data JDBC
  + H2 database
  + Spring Security

### Tests
Was developed with Test Driven Approach.
For tests H2 local database is used. That allows easy switch to any another RDBMS.

### Security
The application manages cash cards which implies need of robust and easy-tested means of security.
So the Basic Authentication method was implemented.

### Data
Cashcards are serialized and stored in relational database.

### RESTful
The application satisfies REST API and gives correct response on each request method.
Additionaly no data leeks are available from server response even in case of some internal error.

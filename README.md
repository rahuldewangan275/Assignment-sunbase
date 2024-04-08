# Assignment Sunbase Task
this is backend side of the assifnment

## Technologies used
- java
- Springboot
- MySql
- Intellij

  ## Security features
  - jwt Authentication
  - Spring Security

#Demo Video
https://github.com/rahuldewangan275/Assignment-sunbase/assets/115481639/151c5812-41bf-49aa-962d-bda01d9f467e

  ## Run on Your System

  ### clone the repository
  ```
   https://github.com/rahuldewangan275/Assignment-sunbase
  ```

  ### open in intellij
  Open IntelliJ IDEA and follow these steps to clone the project:
- Click on "File" in the top-left corner.
- Select "New" and then click on "Project from Version Control."
- Choose "Git" and paste the cloned repository URL.
- Click "Clone" and wait for IntelliJ to download and set up the project.

 ### SetUp MySql Server
 make customerdb named database on your database.
 in application.properties folder set your database config, set server,user,password etc
 ```
spring.datasource.url=jdbc:mysql://localhost:3306/customerdb?createTableIfNotExists=true
spring.datasource.username= your username Eg: root
spring.datasource.password= your password Eg: 12345
spring.jpa.hibernate.ddl-auto=update
server.port=8080
```

### start backend server
run your application on intellij
The backend server should start running, and you should see the application logs in the IntelliJ console.
now setup frontend.

## FrontEnd Repository Link
https://github.com/rahuldewangan275/sunbase-front

```
thanks for visiting
```

  

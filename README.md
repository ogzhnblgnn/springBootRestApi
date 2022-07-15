# springBootRestApi
<br>
LAYERS
<hr/>
● Entities    ➤    City
<br>
● Data Access Layer    ➤    ICityDal, HibernateCityDal(@Repository)
<br>
● Business Layer    ➤    ICityService, CityManager(@Service)
<br>
● RestApi    ➤    CityController(@RestController)

<hr/>

You have to define your mySQL username and password parts in 'src -> main -> resources -> application.properties' file.<br>
Required dependencies are given with 'pom.xml' and the World Database 'world.sql' file at the root folder.<br>
For get the project up: You can run main package as Java Application or Spring Boot Application. <br>
<br>
As you can see in the CityController:<br> <br>localhost:8080/api <br> localhost:8080/api/cities <br> localhost:8080/api/cities/{id} <br> localhost:8080/api/add <br> localhost:8080/api/update <br> localhost:8080/api/delete <br><br>
You can send test requests to these endpoints in Postman. 

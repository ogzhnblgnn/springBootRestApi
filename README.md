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
For get the project up: You can run main package as Java Application or Spring Boot Application.

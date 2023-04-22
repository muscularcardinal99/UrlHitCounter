
# Hi, I'm Abhishek Kushwaha! 👋


## Authors

- [@muscularcardinal99](https://www.github.com/muscularcardinal99)


## 🚀 About Me
I'm a Java developer...


## 🛠 Skills
Java, HTML, Springboot, MySQL...


## DataFlowStructure
in the following Java Program  

~~~
1.Controller
  1.addUserList()
  2.getHitCount()
  3.addHitCount()
2.DAO/Repository
  1.addUser()
  2.addHitOfUser()
  3.getUserData()
3.Services
  1.addUserData()
  2.addUserList()
  3.addHitofUser()
4.Model/DataBase Design
  1.This class contains user Model and its Properties
~~~


## API Reference



#### Add User List

```http
  localhost:8080/api/v1/visitor-count-app/addUserList
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Request Body` | `JSON` | **Required**. a List<User> which is list of users in JSON format |


#### Add Hit to user

```http
 localhost:8080/api/v1/visitor-count-app/username/{userName}/hit
```

| Parameter | Type     | Description                                                     |
| :-------- | :------- | :-------------------------------------------------------------- |
| `Path Variable'      | `String` | Returns user Users hit where userID matches with provided                             userID *Required* userID  |


#### Get Hit Count

```http
 localhost:8080//api/v1/visitor-count-app/username/{userName}/count
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Path Variable`      | `String` |  Returns how many times URL been hit *Required* userName  |


## Documentation for Simple URL Hit Counter Feature using Spring Boot

In this project, a simple URL hit counter feature has been implemented using Spring Boot framework. The project consists of a UrlHitController class with a GET mapping method, which calls the UrlHitService class to increment the hit count of a specific URL. The UrlHitService class is responsible for managing the hit count data and storing it in a UserModel. The application has been tested and pushed to a Git repository for version control. Overall, the project provides a basic implementation of a URL hit counter feature using Spring Boot.




## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muscularcardinal99/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/LoneWolf_ak99)


## Feedback

If you have any feedback, please reach out to us at kushwaha.abhishek1999@gmail.com

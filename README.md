# Swagger codegen

Create the same REST API, but use https://editor swagger.io/ to create your API definition and generate the server code. Choose any java-based server or server framework. that you like. You can either use the online editor or generate the code manually, e.g. using this document: https://github.com/swagger-api/swagger-codegen/wiki/server-stub-generator-howto Make sure that you can deploy/run the generated code. Once your stub is ready - implement the same functionality as described in task #1, but now in java.

Finally, be sure that you can show how your application responds to requests using postman, curt or any other HTTP client.

### *Technologies Used*
* Java
* Maven
* SpringBoot Framework
* Mongodb
* Springfox Swagger UI

### *Implementation of Swagger*
* Implementation of Swagger with SpringBoot and MongoDB
* Added swagger dependencies to task1 existing project
* created a new file called SwaggerConfig.java and annotated it with the @EnableSwagger2 annotation


![image](https://user-images.githubusercontent.com/111385394/227796217-dc37be56-9122-4736-b4de-d94720b3170a.png)

### *Testing of Swagger on localhost*


> * Tested swagger on localhost using url http://8081/swagger-ui.html#/
> * And now I have swagger ui to view all my documentation


![SwaggerUI](https://user-images.githubusercontent.com/111385394/227798645-a6a1881d-f8e1-488b-9a05-44b6917df431.png)


> * In the above UI we can perform all the functionalities that we did in POSTMAN in Task1




###  ___Adding Server in Swagger UI___

![image](https://user-images.githubusercontent.com/111385394/227799491-61a0de1c-5b7c-4bfc-8c30-ae4c3ce5ee82.png)
![image](https://user-images.githubusercontent.com/111385394/227799631-df5a4f9b-9997-48f8-8b06-8aaa482494af.png)

##### Mongodb Database
![image](https://user-images.githubusercontent.com/111385394/227799675-ef19e1ff-85bf-4361-967d-52b515413ddd.png)


### ___fetching all servers in Swagger UI___

![image](https://user-images.githubusercontent.com/111385394/227800375-c12381ca-c875-43ab-b897-f852f8580616.png)
![image](https://user-images.githubusercontent.com/111385394/227800503-069a4a2c-ec50-4d6f-8cbb-a9954aa1bc83.png)


###  ___Deleting Server in Swagger UI___

![image](https://user-images.githubusercontent.com/111385394/227800678-131b604c-33a8-4664-ba3c-f56288575c2f.png)
![image](https://user-images.githubusercontent.com/111385394/227800752-9ae43493-717b-49e7-865d-d5e8068d85c6.png)

##### Mongodb Database after deleting Server
![image](https://user-images.githubusercontent.com/111385394/227799943-e7f757ad-d923-4b60-bfe9-820439b92d2b.png)


###  ___Get Server By Name in Swagger UI___
![image](https://user-images.githubusercontent.com/111385394/227800794-f19bce46-5a21-4fc4-bec3-9bcba7f07bb5.png)
![image](https://user-images.githubusercontent.com/111385394/227800835-bbe34ea3-c699-4171-9f86-047a8be96b47.png)


#### Get the from postman to get the code generated automatically & Used the code form Swagger UI and Tried it on Online Editor
![image](https://user-images.githubusercontent.com/111385394/227802794-a2eb0154-6d68-441d-bc79-dc788b8ad58e.png)
![image](https://user-images.githubusercontent.com/111385394/227802721-7fb1f41e-6507-4b2d-adc9-710f3bcc1537.png)







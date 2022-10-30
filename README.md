# Login-Microservice

This microservice is used to create new users or check if a user already exists. 

To request data from the microservice the user write onto the textfile whether they are creating("create") a new user or if they are logging("login") in followed by the username and passsword. Each of these items is written on a seperate line in this order.
Example call: f.write("login\nusername\npassword")

To recieve data from the microservice the user reads from the same textfile after the microservice has written into. The microservice will write true when creating a user if a new user has been created and false if it has not. When a user is logging in it will return true if the user currently exists if the user does not exist it will write false.

![image](https://user-images.githubusercontent.com/91388662/198897425-05449c18-47a1-4c9a-87ad-edbca49de582.png)

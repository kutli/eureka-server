#EUREKA SERVER


Eureka Server is a discovery server that holds the information about all client-service applications. Every Micro service will register into the Eureka server and Eureka server knows all the client applications running on each port and IP address.


## Run in Local:
The app will start in local server in port 8761.
Access to localhost:8761/login using the following credentials:
```
username: user
password: password
```


## ENV VARS that must be configured in server:
SPRING_USER= username to login eureka dashboard <br />
SPRING_PASSWORD= password to login eureka dashboard <br />
EUREKA_URL= Eureka url where the application has been deployed.

### Example of env vars in heroku
```
SPRING_USER=user
SPRING_PASSWORD=pass
EUREKA_URL=https://my-app-name.herokuapp.com
```

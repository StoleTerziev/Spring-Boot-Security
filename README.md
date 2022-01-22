# Spring-Boot-Security-Jwt

## User Registration, User Login and Authorization process.
The diagram shows flow of how we implement User Registration, User Login and Authorization process.

![diagram_flow](https://user-images.githubusercontent.com/11914457/150651884-7a85c0e8-6a6e-46b3-809e-62e18c3164b8.png)


## Spring Boot Server Architecture with Spring Security

![diagram_flow1](https://user-images.githubusercontent.com/11914457/150651895-10f194d7-fe66-4ea3-8b18-23b9d18e68bf.png)


## Refresh Token

![refresh_token](https://user-images.githubusercontent.com/11914457/150651904-8da481a7-62e5-4485-b1a5-ba5b6ccf7475.png)


## Run Spring Boot application
```
mvn spring-boot:run
```

## Run following SQL insert statements
```
INSERT INTO roles(name) VALUES('ROLE_USER');
INSERT INTO roles(name) VALUES('ROLE_MODERATOR');
INSERT INTO roles(name) VALUES('ROLE_ADMIN');

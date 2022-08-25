# User_login_registration
Java tutorial, learning how to develop a complete backend app user login and registration + email verification with expire function using Spring Boot.

### Example of a request using Postman

![postmanexample](https://user-images.githubusercontent.com/74435367/186712626-4258d931-7cf6-4c1b-96d8-b50bee80fe63.png)



### CURL

```
curl --location --request POST 'localhost:8080/api/v1/registration' \
--header 'Content-Type: application/json' \
--data-raw '{
    "firstName": "Daniel",
    "lastName": "Matt",
    "email": "example@example.com",
    "password": "password"
}'
```


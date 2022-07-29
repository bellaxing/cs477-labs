# Lab 8 - Authentication & Authorization
1. Continue Lab 8 based on Lab 7 to implement the features below for RESTful Application:
    1. Add a login feature which username and password. If logged in successfully, return JWT, otherwise, error message.
    2. For all CRUD operations on Books, they have to be authenticated. If call APIs withou JTW, return 401 unauthorized. With incorrect JWT, return 403 Forbidden. Only with correct, return JSON data
    3. Use Postman test all APIs
2. Client: add login/logout features. And make sure only logged in users can CRUD books.

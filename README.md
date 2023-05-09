# CRUD Implementation with Java and Docker

## Enter the Directory

`cd demo/`

## Connect to Database and Start Application

Run `docker compose up -d` and the application is served at `localhost:8080/api/users`

You can make different HTTP requests to the server:

### Retrieve all users

send a `GET` request to the `/users` endpoint

Intially, the response is an empty array. After adding some user data, you can make this request and see the response again.

### Retrieve one user

send a `GET` request to the `/users/:id` endpoint

### Add a new user

send a `POST` request to the `/users` endpoint with the user data in the request body

### Delete a user

send a `DELETE` request to the `/users/:id` endpoint, where :name is the name of the user to be deleted

### Update a user

send a `PUT` request to the `/users:id` endpoint with the updated user data in the request body

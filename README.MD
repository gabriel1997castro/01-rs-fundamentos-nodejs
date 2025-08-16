# Learning

## How to change the way to import files

CommonJs => require
ESModules => import

## Routes

Examples

- Create users
- List users
- Edit users
- Remove users

We use http methods

- GET => Search information, get info
- POST => Create an information in the backend
- PUT => Update something on backend
- PATCH => Update an specific information
- DELETE => Delete something

### HEADERS

We can send metadata here like saying that the response is a JSON

Example
GET /users => getting information of users in the backend

### Status code

100 - 199 => Informational
200 - 299 => Successful responses -> 200 is default
300 - 399 => Redirection messages
400 - 499 => Client error responses
500 - 599 => Server error responses

## Stateful and Stateless

Stateful applications depends on the app keep running to have the info
Stateless saves in some database

## 3 ways to send info

- Query parameters:
  - URL stateful - we could send a url from a list of users filtered and sorted to another person
  - http://localhost:3333/users?userId=1
- Route parameters:
  - GET http://localhost:3333/users/1 - get user 1
  - DELETE http://localhost:3333/users/1 - delete user 1
  - 1 is a route parameter and it should identify a resource.
- Request body:
  - We can use to send form information (HTTPs)

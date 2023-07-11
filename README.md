# flask-crud-postgres

#### This project is basically made for Python, which uses FLASK and Postgres ,which includes the CRUD operation.


####
### POST
curl -X POST localhost:4000/users    -d '{"username":"test1@test.com" , "email":"test1@test.com"}'   --header "Content-Type: application/json"

### GET
curl -X GET  localhost:4000/users    

### PUT
curl -X PUT localhost:4000/users/:id   -d '{"username":"test1@test.com" , "email":"test1@test.com"}'   --header "Content-Type: application/json"

### DELETE
curl -X DELETE localhost:4000/users/:id 



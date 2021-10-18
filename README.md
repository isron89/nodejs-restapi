# Nodejs-Restapi

Sample RestAPI with Node.js HTTP Server

Documentation:
1. npm run start -> running basic http server with 200 response code. 
example request : curl -i -X GET http://localhost:5000/

2. npm run server -> handle http request method GET,POST,PUT,DELETE. 
example request : curl -i -X GET http://localhost:5000/, 
curl -i -X PUT http://localhost:5000/, 
curl -i -X DELETE http://localhost:5000/, 
curl -i -X POST -H "Content-Type: application/json" -d "{"name":"isron","age":"21"}" http://localhost:5000

3. npm run route-server -> http server according to url path. 
example request : curl -i -X GET http://localhost:5000/, 
curl -i -X GET http://localhost:5000/about 
curl -i -X POST -H "Content-Type: application/json" -d "{"name":"isron","age":"21"}" http://localhost:5000/about

4. npm run response-server -> http server handling by response

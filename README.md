# Nodejs-Auth

## Node.js Authentication App
 I worked previously with Node.js as I created a project that has basic RESTful API using node and express and mongodb by using mogoose and Atlas,
but I haven’t gotten into authentication and containerization an app.

I used JWT for token authentication and docker for containerization

That gave me a boost of understanding various authentication methods and containerization and in the future, I may extend it to use something like passport.js to create sessions and to  support other authentaication methods like  OpenID and OAuth

## How to Run
First make the .env file for secret configuration and environment variables for the Database.

you have two options whether to use docker by:
Building the image and Runing the container
```
docker build -t <image-name> .
docker run -d -p <host-port>:<container-port> <image-name>
```
Put in the image name that you want and the mapping between the host and container port to access the container from outside.

OR
```
npm install 
npm run dev
```

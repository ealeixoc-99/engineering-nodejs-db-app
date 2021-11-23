# engineering-nodejs-db-app
Efrei - Engineering - TP Create docker-compose nodejs db

I encountered some problem at the beginning. Indeed, my database was generated after the nodejs project (despite the depend_on). 
It was therefore necessary to add a docker-compose healthcheck to verify that the database is launched before managing the node part.

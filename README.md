# Docker-Test

To Build the docker file run 
docker-compose up --build 

test buy running http://localhost:8080 

This should allow local changes to the index file for dynamic editing of the web content 

when compling the the production server you will need to specify the docker create file 

docker-compose -f docker-compose-prod.yml up --build 

the production server runs on port 80 

this example uses the nginx docker file 



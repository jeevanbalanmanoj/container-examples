# container-examples

#This is a very basic example project to see how docker containers work 

#Step 1 : Navigate to the folder containing docker-compose.yml file in cmd and execute the following command   
# docker-compose up
# The necessary dependencies mentioned in requirements.txt ( Dependencies for python like flask) will be downloaded and setup. The base image mentioned in Dockerfile will also get downloaded and setup

#Step 2 : Once the container is up and running hit the url http://localhost:5001/ and you will see a list of products.
# Since we are using volumes in docker we can actually change the api.py file and see the changes immediately without performing a container restart.

#The volume configuration is extremely useful during development and is confgured in the docker-compose.yml file

# Capitec-User-Service-Submissions

As a Kubernetes administrator you are given access to 3 images, which together form a microservice-based application named: Capitec User Service. This is a simple application to used to onboard new users, as leads, so that different business units can pitch products to them. The application has the following components: 

- <b>Postgres database:</b> 
   Image available from DockerHub 

   Image referenced as: postgres 

   Setup to listen on port: 5432 

- Spring Boot Backend Service  

  Images available from DockerHub 
  
  Windows-compatible image: thapeloseema/capitec-user-service:backend-amd64 
  
  Mac-arm compatible image: thapeloseema/capitec-user-service:backend-arm64 
  
  Setup to listen on port: 8080 

- Angular Frontend Service  

  Images available from DockerHub 
  
  Windows-compatible image: thapeloseema/capitec-user-service:frontend-windows-latest 
  
  Mac-ARM compatible image: thapeloseema/capitec-user-service:frontend-latest 
  
  Setup to listen on port: 4200 

 

You are tasked with deploying this application on a local Kubernetes cluster such that the front-end application is available from outside of the Kubernetes cluster, the front-end can communicate internally with the backend, and the backend can communicate internally with the database. We need to have 3 instances of the front end always running, 4 instances of the backend, and 2 instances of the databases. 

You will have received an invite to the Geeks4Learning Capitec-User-Service Repository, please create a branch in the repository, and name it following this format; your name and surname as follows: 

thapelo_seema 

This is where you must push all the code in your solution, once you have tested it on your machine. 

The working solution will have an externally accessible website where you can add users as shown below: 

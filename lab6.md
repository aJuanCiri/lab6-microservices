#The two microservices are running and registered (two terminals, logs screenshots).
![Web Service](registration.png "Web Service")
![Web Service](account.png "Web Service")
![Web Service](web.png "Web Service")

#The service registration service has the two microservices registered (a third terminal, dashboard screenshots)
![Registration Service](accountRegistrado.png "Web Service")
![Registered 2 microservices](webRegistrado.png "Registered 2 microservices")
![Registered 2 microservices](registrados.png "Registered 2 microservices")

#A second account microservice is running in the port 4444 and it is registered (a fourth terminal, log screenshots).
![Account Service 2](capturaFinal.png "Account Service 2")

#A brief report describing what happens when you kill the microservice with port 2222. Can the web service provide information about the accounts? Why?
When our microservice is closed, it returns an error message, and it asks the register service in order to obtain a working account service.
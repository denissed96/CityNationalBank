# City national Bank 

Take home task for CNB 


# Task 1 

Implentation of Postgres, httpd and RabbitMQ. 
In order to run this file make sure you include your `.env` file with the following required variables: 
 - RABBITMQ_DEFAULT_USER
 - RABBITMQ_DEFAULT_PASS
 - POSTGRES_PASSWORD
 - POSTGRES_USER
 - POSTGRES_DB
 
 Once this is done run: `docker-compose up` 
 This will create the three services in the following ports: 
 
 - httpd : `localhost:8080`
 - RabbitMQ : `localhost:15672`
 - postgres: `localhost:5000`


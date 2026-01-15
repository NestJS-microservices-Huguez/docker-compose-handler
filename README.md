
<p align="center">
   <img decoding="async" width="659" height="440" src="https://www.docker.com/app/uploads/2023/08/logo-guide-logos-1.svg" title="Huguez Microservices Project" alt="Huguez Microservices Project" >
</p>

<h2 align="center">Docker Compose Handler </h2>


1.- Clone the repository
```
git clone https://github.com/NestJS-microservices-Huguez/docker-compose-handler.git
```

2.- rename .env.template to .env and write variables
```
CLIENT_GATEWAY_PORT         = **********

PRODUCTS_MS_PORT            = **********
PRODUCTS_MS_DATABASE_URL    = **********

ORDERS_DB_POSTGRES_PORT     = **********
ORDERS_DB_POSTGRES_USER     = **********
ORDERS_DB_POSTGRES_PASSWORD = **********
ORDERS_DB_POSTGRES_DB       = **********

ORDERS_MS_PORT              = **********
ORDERS_MS_DATABASE_URL      = **********
```

3.- Execute command 
```
docker compose up --build
```

!!! Tip
      If do you need remove previous container you can execute
      ```
      docker compose down -v
      ```
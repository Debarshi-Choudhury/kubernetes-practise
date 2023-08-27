Deploying a microservice application in kubernetes using deployments and services.

Components of the application:

1. A redis db
2. A postgres db
3. A voting app
4. A result app
5. A worker app

<br>
Conections required:

1. An external user should be able to connect to the voting app
2. An external user should be able to connect to the result app
3. The voting app should be able to connect to the redis db
4. The result app should be able to connect to the postgres db
5. The worker app should be able to connect to the redis db
5. The worker app should be able to connect to the postgres db
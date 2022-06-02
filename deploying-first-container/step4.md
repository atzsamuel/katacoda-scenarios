# Step 4 - Accesing Redis

```sh
#We would prefer to run multiple REDIS instance and configure the application depending on which port Redis is running on
$docker run -d --name redisDynamic -p 6379 redis:latest
#For view wich port has been assigned we use
$docker port redisDynamic 6379
$docker ps
```
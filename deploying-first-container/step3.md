# Step 3 - Accesing Redis

```sh
#Redis runs on 6379 port, we need instance to be listening on the port using -p <host-port>:<container-port> option
#Tip We can specify a particular IP ADDRESS when we define the port mapping, -p 127.0.0.1:6379:6379
$docker run -d --name redisHostPort -p 6379:6379 redis:latest
```
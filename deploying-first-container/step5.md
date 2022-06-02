# Step 5 - Persisting Data

```sh
# for this we need to use VOLUMES is done using the option  -v <host-dir>:<container-dir>
$docker run -d --name redisMapped -v /opt/docker/data/redis:/data redis
# Docker allows you to use $PWD as a plhaceholder for the current directory
$docker run -d --name redisMapped -v "$PWD/data":/data redis
```
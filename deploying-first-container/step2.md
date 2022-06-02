
# Step 2 - Finding Running Containers

```sh
#For view launched container is running in the background
$docker ps
#For view more details such as IP address
$docker inspect <friendly-name|container-id>
#For view logs  <friendly-name|container-id>
$docker logs 1be3d5a6e86e
```
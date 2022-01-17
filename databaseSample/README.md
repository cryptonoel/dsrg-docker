# Setting up

To setup the necessary components **WITHOUT** starting any of the containers run
the below command

```bash
docker-compose up --no-start
```

To only build the custom image run the below command

```bash
docker-compose build
```

# Start

To start the services run the below command

```bash
docker-compose start
```

# Stop

To stop the services run the below command

```bash
docker-compose stop
```

# Clean Up

To remove any stopped containers run the below command

```bash
docker-compose down
```

If the volumes needs to be removed as well, run the below command

```bash
docker-compose down -v --rmi local
```

# Start a bash instance on a container

```bash
docker exec -it <container_name> bash
```

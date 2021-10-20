# Example RabbitMQ setup with consul and docker-compose

This would use vanilla rabbitMQ images to set up a local cluster of rabbit
Consul would be used to synchronize and discover nodes

# How to

Use `docker-compose up -d` to start.

Use `docker-compose logs` to read logs.

Use `docker-compose down` to stop.

## Important

Make sure you have a decent version of docker-compose.

Make sure you have docker on your system.

You could start is as root or user within proper group
(ex. docker - search for rootless docker configuration on the internet).

You could use it on windows as well... probably... I am not sure. Not tested.
If you are a software developer you should consider a switch to a not-windows operating system.

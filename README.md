# Portainer Docker Container

## About

Based on the [official documentation](https://portainer.readthedocs.io/en/stable/deployment.html#deploy-portainer-via-docker-compose).

Portainer is a web UI for managing your docker containers.

## Deploy

Start Portainer as a Docker Swarm service by running the following command on your manager node:
```bash
$ docker stack deploy -c docker-compose.yml prtnr
```

> Note, that this service uses a *required* manager-node placement constraint 

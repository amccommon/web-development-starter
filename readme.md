# Folder structure
## project/
1. docker-compose.yml
### client/
1. dockerfile
2. .dockerignore
3. src/
4. package.json
### server/
1. dockerfile
2. .dockerignore
3. src/
4. package.json

# Instructions
1. Run docker-compose up to start each container.
2. Run docker-compose ps to inspect the running services
3. Run docker-compose logs to dump the logs of all the running services
4. Run docker-compose stop to stop all the services
5. Run docker-compose down --volumes to bring everything down removing the containers entirely with the data volume.

More information is here

[Dockerizing MERN 1](https://medium.com/mozilla-club-bbsr/dockerizing-a-mern-stack-web-application-ebf78babf136)
[Dockerizing MERN 2](https://simplernerd.com/docker-mern-development/)
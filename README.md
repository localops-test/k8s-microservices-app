# k8s-microservices-app

Simple app that connects front end with back end and acts as a micro service.
Front end serves the backend through backend consumer.

## Running the app:

### Running it individually:

```
cd frontend
python3 app.py

cd backend
python3 app.py
```

Running it as a docker image using docker compose:

```
docker network create pr_network
```
### verify the docker network
```
docker network ls | grep pr_network
```
```
cd deployment-docker
docker-compose up --build
```


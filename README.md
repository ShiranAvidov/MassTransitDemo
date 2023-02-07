# MassTransitDemo

## Getting Started

1. Replace `<<LOGZIO_TOKEN>>` in `config.yaml` to your Logz.io tracing token.
2. Run (you need to be where the docker-compose file is located): 
```shell
docker compose up
```
3. In your machine go to `http://localhost:5000/swagger/index.html` and press try and execute on each dispatch.
4. Go to your Logz.io account, into tracing and search for the 2 services: `api` and `service`.

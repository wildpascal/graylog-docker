# Graylog Docker
Complete docker-compose project for a graylog installation.

## Configuration
Copy the .env.dist file and replace the config parameters with yours.
```{r, engine='bash', count_lines}
cp .env.dist .env
```

## Run
To run the graylog installation execute the following command:
```{r, engine='bash', count_lines}
docker-compose up -d
```
### Access graylog

You can access graylog http://127.0.0.1:9000

## Todos
- Create a proxy to allow external access to graylog via a domain.

## Further informations

- https://www.docker.com/
- http://docs.graylog.org/en/2.1/pages/installation/docker.html

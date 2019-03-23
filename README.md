# artifactory

## Run

```none
docker run -d -p 8081:8081 \
  --volume artifactory-data:/artifactory/data \
  --volume artifactory-logs:/artifactory/logs \
  --volume artifactory-backup:/artifactory/backup \
  --name artifactory-oss \
  artifactory
```

## Access

[http://localhost:8081](http://localhost:8081)

## Build
```none
docker build -t artifactory .
```

See [Dockerfile](Dockerfile).

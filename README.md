# Run OpenTelemetry Collector and Observablity Components
```
docker compose --env-file .env -f docker-compose.yaml up --build
```




Troubleshooting
```
DOCKER_BUILDKIT=0 docker build . -f Dockerfile.opensearch --no-cache
https://opensearch.org/docs/latest/security/configuration/disable-enable-security/
```

telemetrygen logs --otlp-endpoint localhost:4318 --logs 1 --workers 1 --otlp-insecure --otlp-http


go mod tidy
GOWORK=off go run .  
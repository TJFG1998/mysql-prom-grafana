# Resume
In this repository is a template of a fully functional docker based database analyser.

# Requirements

- Docker 19.03 or higher
- Two volumes:
    - grafana-storage
    - prometheus-storage

# Volumes

`docker volume create grafana-storage`
`docker volume create prometheus-storage`

# Start and Stop

To start -> `docker-compose up -d`
To stop -> `docker-compose down -d`

Docker image default configurations for PortainerIO server
================================

References: https://portainer.io

## Run Instructions

### Run container in swarm mode (preferred method)

    docker stack deploy --compose-file=portainer-agent-stack.yml portainer

### Run container in compose mode

    docker-compose up -d

You should be able to access the webpage on http://localhost:9000

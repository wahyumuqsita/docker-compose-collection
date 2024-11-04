# Docker Compose
This repository is my personal collection of Docker Compose configurations. I use it to streamline and support various local development environments.

Each configuration is tailored for different services and setups, allowing me to quickly spin up and manage isolated development environments on my local machine. This collection is especially useful for testing, debugging, and experimenting with different application architectures without impacting other systems.

## How to run 
1. install docker and docker compose 
   https://docs.docker.com/engine/install/ 
   you can install docker desktop also 
   https://www.docker.com/products/docker-desktop/

2. run docker compose 
   ```
   docker compose -f ./{service}/docker-compose.yaml up -d
   ```
# 🚀 Dockerized Vite Frontend

This project is a **Vite-based frontend** that has been **Dockerized** for easy deployment and development.  
The frontend was originally downloaded from GitHub, and Docker support was added to containerize the application.

## 🛠️ Commands Use To Dockerized

- **`docker build -t front-end .`**: Builds the Docker image and tags it as `front-end`.
- **`docker images`**: Lists the Docker images on your system.
- **`docker run --name front-end_c -p 3000:5173 --rm -v /app/node_modules -v ${PWD}:/app -e CHOKIDAR_USEPOLLING=true   sha256:fb82079c3eff6723def3abcf15eb50f3489d80f75e99ac8a389958895d36de93`**: Runs the container, mapping the ports and enabling hot-reloading.
- **`docker stop front-end_c`**: Stops the container manually.
- **`docker ps`**: Lists all running containers.

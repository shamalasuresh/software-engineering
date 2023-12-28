## Commands

### System

| Command          | Description                                                       |
| ---------------- | ----------------------------------------------------------------- |
| `docker info`    | Display system-wide information.                                  |
| `docker version` | Show the Docker version information.                              |
| `docker-compose` | Utilize Docker Compose for managing multi-container applications. |

### Registry and Repository

| Command         | Description                                   |
| --------------- | --------------------------------------------- |
| `docker login`  | Log in to a Docker registry                   |
| `docker logout` | Log out from a Docker registry                |
| `docker search` | Search for an image on Docker Hub             |
| `docker pull`   | Pull an image or a repository from a registry |
| `docker push`   | Push an image or a repository to a registry   |

### Image

| Command          | Description                                    |
| ---------------- | ---------------------------------------------- |
| `docker build`   | Build an image from a Dockerfile               |
| `docker images`  | List all available images on the local machine |
| `docker rmi`     | Remove one or more images                      |
| `docker history` | Show the history of an image                   |
| `docker tag`     | Tag an image into a repository                 |

### Container Lifecycle

| Command          | Description                                                        |
| ---------------- | ------------------------------------------------------------------ |
| `docker create`  | Create a new container                                             |
| `docker run`     | Run a command in a new container                                   |
| `docker start`   | Start one or more stopped containers                               |
| `docker stop`    | Stop one or more running containers                                |
| `docker restart` | Restart a running container                                        |
| `docker pause`   | Pause processes in a running container                             |
| `docker unpause` | Unpause processes in a paused container                            |
| `docker kill`    | Kill one or more running containers                                |
| `docker rm`      | Remove one or more containers                                      |
| `docker rename`  | Rename a container                                                 |
| `docker exec`    | Run a command in a running container                               |
| `docker ps`      | List running containers.                                           |
| `docker ps -a`   | List all containers.                                               |
| `docker logs`    | Fetch the logs of a container.                                     |
| `docker inspect` | View detailed information about a container or image.              |
| `docker stats`   | Display a live stream of resource usage statistics for containers. |


### Network

| Command                     | Description                                          |
| --------------------------- | ---------------------------------------------------- |
| `docker network ls`         | List all available networks                          |
| `docker network create`     | Create a new network                                 |
| `docker network inspect`    | Display detailed information on one or more networks |
| `docker network connect`    | Connect a container to a network                     |
| `docker network disconnect` | Disconnect a container from a network                |

### Volume

| Command                 | Description                                         |
| ----------------------- | --------------------------------------------------- |
| `docker volume ls`      | List all available volumes                          |
| `docker volume create`  | Create a new volume                                 |
| `docker volume inspect` | Display detailed information on one or more volumes |
| `docker volume rm`      | Remove one or more volumes                          |



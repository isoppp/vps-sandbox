
## Basics

- `docker run <IMAGE_NAME>`

- add option
    - `docker run -it -p 8080:80 <IMAGE_NAME> /bin/bash`

    - port is <localhost:container>
    - after boot /bin/bash
    - `-i, --interactive`
        - Keep STDIN open even if not attached
    -  `-p, --publish value`
        - Publish a container's port(s) to the host (default [])
    -  `-t, --tty`
        - Allocate a pseudo-TTY

- `docker ps -a` show list boot docker container
- `docker attach <CONTAINER_ID>` attach to running container.
- `docker build -t <NAME>:<TAG> <Dockerfile ROOT>`
- `docker images` show docker image list
- `docker rmi <IMAGE_ID>` delete image
- `docker rm `docker ps -a -q`` rm all container
- `docker rm <CONTAINER_ID>` rm single container


## Refers

- nginx
https://github.com/nginxinc/docker-nginx/tree/8921999083def7ba43a06fabd5f80e4406651353/mainline/alpine

- node
https://github.com/mhart/alpine-node

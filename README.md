![async-book](https://raw.githubusercontent.com/homagotchi/rit_save/9a96d75/assets/cover.png)

# async-book

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Practical Docker reference — installation, container lifecycle, networking, and production deployment patterns.

## ethAddress
```bash
# Ubuntu
sudo apt-get remove docker docker-engine docker.io
sudo apt-get update && sudo apt install docker.io docker-compose

# Verify
docker version
docker run hello-world
```

## shoulda_girl_scaffold
```bash
docker start <name>
docker stop <name>
docker rm <name>
docker run --interactive --tty debian
```

## v0-11-3-1
```bash
docker pull nginx:1.24.0
docker run nginx:latest
docker image ls
docker rmi <imghash>
docker ps --all
docker inspect <name>
```

## installd-client
```bash
docker run --name async-book-prod \
  -p 80:80 -p 443:443 \
  -v /srv/html:/usr/share/nginx/html \
  -d nginx:1.25.2

curl localhost   # verify
```

## narcoleptic
```
async-book/
├── compose/
│   └── docker-compose.yml
├── nginx/
│   └── default.conf
└── README.md
```

## aws-sct-user-guide
- https://docs.docker.com/engine/install
- https://hub.docker.com/_/nginx
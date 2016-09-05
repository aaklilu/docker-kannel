# Docker Kannel
Dockerized(Containerized) kannel server

You can build and run the image with docker command as
```bash
docker run -p 13013:13013 -p 13000:13000 kannel
```

Or
You can use docker-compose in this repo to just build and run kannel.

If you want to bring up both [asterisk](https://github.com/antenehrepos/docker-asterisk) and kannel with docker-compose, please look at [this](https://github.com/antenehrepos/docker-telephony) repo.

# Docker Kannel
Dockerized(Containerized) kannel server

### Usage
You can simply run the server as follows

```bash
docker run -d -p 13013:13013 -p 13000:13000 antenehrepos/docker-kannel
```

Or 

Build and run the image from the docker file with docker command like so
```bash
docker build -t kannel
docker run -p 13013:13013 -p 13000:13000 kannel
```

Or

You can use docker-compose in this repo to just build and run Kannel.

### Copyright and license
    A docker image to run Kannel server

    Copyright (C) 2016, Anteneh Aklilu

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see http://www.gnu.org/licenses/.

[![](https://images.microbadger.com/badges/image/antenehrepos/docker-kannel.svg)](https://microbadger.com/images/antenehrepos/docker-kannel "Get your own image badge on microbadger.com")

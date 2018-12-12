# Oracle Instant Client Dockerfile
This repository contains **Dockerfiles** of Oracle Instant Client on Oracle Linux 7 for [Docker](https://www.docker.com/)'s [automated build](https://hub.docker.com/r/remulito/oracle-instantclient/) published to [Docker Hub](https://hub.docker.com/).

File is based on https://github.com/oracle/docker-images/blob/master/OracleInstantClient/dockerfiles/12.2.0.1/Dockerfile and uses https://github.com/bumpx/oracle-instantclient

## What is Oracle Instant Client?

Free, light-weight and easily installed Oracle Database tools, libraries and SDKs for building and connecting client applications to local or remote Oracle Databases.

## Installation

1. Install [Docker](https://www.docker.com/).

2. Download [automated build](https://hub.docker.com/r/remulito/oracle-instantclient/) from [Docker Hub](https://hub.docker.com/): 

```bash
docker pull remulito/oracle-instantclient:12.2.0.1
```
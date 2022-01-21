# docker-toolbox

This is my personal "toolbox" used in docker / k8s environments.
It contains some useful packages and can be run for have a ready to use console.

Packages included:
 - ruby 2.7
 - wget
 - curl
 - git
 - htop
 - nano
 - tmux
 - zip/unzip
 - lbzip2
 - bzip2
 - traceroute
 - ping
 - dig
 - PostgreSQL client (pg_dump) for versions 9.6 -> 12
 - MySQL client (mysqldump) for versions 5.7+
 - Clickhouse client for versions 19+
 - Docker CLI

## Usage

```
docker run -d --name toolbox -v /var/run/docker.sock:/var/run/docker.sock leen15/toolbox
docker exec -it toolbox bash
```
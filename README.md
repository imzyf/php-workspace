# My PHP Workspace Base Image

- [GitHub php-workspace - actions](https://github.com/imzyf/php-workspace/actions/)
- [DockerHub php-workspace - tags](https://hub.docker.com/repository/registry-1.docker.io/yifans/php-workspace/tags?page=1&ordering=last_updated)

## laradock/workspace Origin

- https://github.com/laradock/workspace
- https://hub.docker.com/r/laradock/workspace
- https://raw.githubusercontent.com/laradock/workspace/master/Dockerfile-7.1
- https://raw.githubusercontent.com/laradock/workspace/master/Dockerfile-7.4
- https://raw.githubusercontent.com/laradock/workspace/master/Dockerfile-8.1

## laradock/laradock Origin

- https://github.com/laradock/laradock
- https://github.com/laradock/laradock/tree/master/workspace

## use

```bash
docker run -v $PWD:/var/www --rm laradock-workspace:latest php -m
docker run -v $PWD:/var/www --rm yifans/php-workspace:main-my-7.1 php -m
```

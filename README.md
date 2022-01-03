[![Docker Image CI](https://github.com/hiflohDocker/nginxhttp_reverse_docker/actions/workflows/build.yml/badge.svg)](https://github.com/hiflohDocker/nginxhttp_reverse_docker/actions/workflows/build.yml)
# nginxhttp_reverse_docker
container redirecting all requests to https except /.well-known/acme-challenge

## volumes
- /var/www/cert maped to /.well-known/acme-challenge

# docker Traefik test

This is a test repository trying to migrate Traefik from 1.7 to 2.1.

**Disclaimer:** It's not working yet.

## Purpose

Deploy a global proxy as traefik stack [traefik-docker-compose.yml](traefik-docker-compose.yml), then use it from other stacks [jenkins-docker-compose.yml](jenkins-docker-compose.yml).

Traefik stack also includes a whoami service to test th proxy.

## Current status

Whoami service works, maybe to be defined inside the Traerfik stack, but services in other stacks don't (Jenkins stack).

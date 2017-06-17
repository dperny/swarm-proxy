# Swarm Proxy

## About

Swarm Proxy is a program for managing Docker Swarm services behind a reverse 
proxy. It uses the Docker events stream to monitor for services being created 
and removed, and then uses Swarm Configs to update a reverse proxy service to 
correctly route traffic to those services. It is stateless.


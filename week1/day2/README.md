# Week 1 Day 2 - Docker Microservice

## Docker Hub Image

My Docker Hub image:

https://hub.docker.com/r/prasunsedaii/my-web-app

## Project Files

- `server.py` — Python microservice.
- `Dockerfile` — Instructions for building the Docker image.

## Course Environment Verification

The following tools were verified inside the course Docker container:

- AWS CLI: 2.37.11
- Azure CLI: 2.91.0
- Terraform: 1.9.0
- Python: 3.12.3
- Java: 21.0.12.1

## Docker Images Evidence

Command executed:

```powershell
docker images
```

Output from my local Docker environment:

```text
IMAGE                        ID             DISK USAGE   CONTENT SIZE
PrasunSedaii/my-web-app:v1   a55e9098c048   92.8MB       23MB
alkimi/ccd-course:week1      c25d24c12b11   3.67GB       816MB
hello-world:latest           5e2309035332   25.9kB       9.49kB
my-web-app:v1                a55e9098c048   92.8MB       23MB
prasunsedaii/my-web-app:v1   a55e9098c048   92.8MB       23MB
ubuntu:latest                f144425ff09b   162MB        45.6MB
```
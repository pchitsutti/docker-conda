# docker-conda
Docker image for bioconda environment

Usage:

Build docker image
```sh
docker build -t docker-conda .
```

Install bowtie
```sh
docker run docker-conda conda install-y bowtie
```

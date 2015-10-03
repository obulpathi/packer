# Build Docker image by [Packer](http://www.packer.io/)

[You can build Docker images without Dockerfile](http://www.packer.io/docs/builders/docker.html#toc_4).

## Chef

Build docker image with chef provisioning

```
$ packer build chef.json
```

Check it.

```bash
$ docker run -t -i obulpathi/packer-chef:0.1 bash

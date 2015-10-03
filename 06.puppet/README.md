# Build Docker image by [Packer](http://www.packer.io/)

[You can build Docker images without Dockerfile](http://www.packer.io/docs/builders/docker.html#toc_4).

## How to build

Run docker

### Puppet

Build docker image with puppet provisioning

```
$ packer build machine_puppet.json
```

Check it.

```bash
$ docker run -t -i tcnksm/packer-puppet:0.1 bash
```

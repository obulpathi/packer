# Build Docker image by [Packer](http://www.packer.io/)

[You can build Docker images without Dockerfile](http://www.packer.io/docs/builders/docker.html#toc_4).

### Ansible

Build docker image with ansible provisioning

```
$ packer build ansible.json
```

Check it.

```bash
$ docker run -i -t obulpathi/packer-ansible:0.1 bash
```

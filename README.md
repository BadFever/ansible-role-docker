# ansible-role-docker

[![Build Status](https://travis-ci.org/BadFever/ansible-role-docker.svg?branch=master)](https://travis-ci.org/BadFever/ansible-role-docker)

Installs [Docker]([https://www.packer.io](https://www.docker.com/)).

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

The docker package to install.

```YAML
docker_package: "docker-ce"

```

The docker repo url.

```YAML
[packer_arch: "amd64"](docker_yum_repo_url: https://download.docker.com/linux/centos/docker-ce.repo)
```

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - ansible-role-docker

## License

MIT

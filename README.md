# Ansible Role Docker Container

Install a docker container

## Role Variables

<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD034 -->
| group | variable | default | description |
| --- | --- | --- | --- |
| basic | `docker_container_name` | | the value for `--name` |
| basic | `docker_container_image` | | the `IMAGE` for `docker run` |
| basis | `docker_container_ports` | | the value for `--publish` |
| basic | `docker_container_command` | | the `COMMAND` for `docker run`|
| basic | `docker_container_restart_policy` | | the value for `--restart` |
| basic | `docker_container_env` | `[]` | the values for `--env` |
<!-- markdownlint-enable MD033 -->
<!-- markdownlint-enable MD034 -->
